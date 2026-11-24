# 第三者ソフトウェアのライセンス表記（THIRD-PARTY NOTICES）

ツナグ（Tsunagu）は、以下の第三者ソフトウェアを利用・同梱しています。各著作権者に感謝します。

---

## Qt / PySide6（Qt for Python）

- 本製品は **Qt**（The Qt Company 他）を **PySide6** 経由で利用し、Qt のライブラリを同梱しています。
- 利用条件：**GNU Lesser General Public License v3（LGPLv3）**。
- **Qt ライブラリの差し替え（再リンク）について**：本製品はインストール先の `_internal\PySide6\` 以下に
  Qt の DLL を個別ファイルとして同梱しています。利用者は、対応するバージョンの Qt ライブラリを
  自身で用意して該当ファイルを置き換えることができます（LGPLv3 が求める再リンクの自由）。
- Qt のソースコード・ライセンス全文の入手先：
  - ソース：<https://download.qt.io/>（および <https://code.qt.io/>）
  - LGPLv3：<https://www.gnu.org/licenses/lgpl-3.0.html>
- 同梱している Qt／PySide6 のバージョン：PySide6 6.11 系（Qt 6 系）。
  ※ GPL のみで提供される Qt モジュール（Qt Charts・Qt Virtual Keyboard 等）は同梱していません。

## cryptography

- 用途：将来のライセンス照合（Ed25519）向けの下地（現在は無効）。
- ライセンス：Apache License 2.0 / BSD-3-Clause（デュアル）。
  - <https://github.com/pyca/cryptography/blob/main/LICENSE>

## Python

- 本製品は Python ランタイムを同梱しています。
- ライセンス：Python Software Foundation License。
  - <https://docs.python.org/3/license.html>

## HitoYukaCommon（共通起動演出）

- 起動時のブランド演出は HitoYuka 自身の共通ライブラリ・アセット（ひとみ／ゆかりのイラスト等）で、
  HitoYuka が著作権を保有します。第三者ライセンスではありません。

---

## ビルド時のみ利用（配布物には含まれません）

- **Pillow**（アイコン生成 `tools/make_brand.py`）：HPND License。配布する実行ファイルには同梱していません。
- **PyInstaller**（パッケージング）、**Inno Setup**（インストーラー作成）。

---

本表記は配布形態により追記・更新します。ツナグ自身のライセンスは [README.md](README.md) を参照してください。
