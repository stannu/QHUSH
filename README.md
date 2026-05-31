# QHush

**5×5の格子配列に、すべての効率を凝縮する。**

QHushは、Seeed Studio XIAO nRF52840を搭載した、ミニマルかつ高機能な25キーの一体型（非分割）無線メカニカルテンキーです。コンパクトな5×5の格子配列（Ortholinear）の中に、洗練されたマルチOS対応のレイヤー設計と、最新のZMK Studioによるリアルタイムなキーマップカスタマイズ環境を融合させています。

## Features
* **Minimalist & Industrial Design:** 5×5の極限まで無駄を削ぎ落としたグリッド配置。インダストリアルな美学に基づいた、ミニマルで研ぎ澄まされたデザインです。
* **Wireless Freedom (BLE):** Bluetooth LEによる完全ワイヤレス接続に対応。スマートなスリープ機能により待機電力を抑え、バッテリーライフを最大化します。
* **MCU:** Seeed Studio XIAO nRF52840
* **Controls:** 25 x Mechanical LP Switches (5×5 Matrix)
* **Underglow:** 4 x RGB LEDによる美しいアンダーグローを搭載。
* **Firmware:** ZMK Firmware (最新の **ZMK Studio** による画面上でのリアルタイムキーマップ変更に完全対応)

## Layer Design & Navigation
QHushは、コンパクトな25キーでありながら、強力なレイヤー設計（Mac用レイヤー 0〜3、Windows用レイヤー 4〜7）とコンボ入力を組み合わせることで、フルサイズテンキー以上の機能性と効率的なワークフローを実現しています。

* **Layer 0 (Mac Base) / Layer 4 (Win Base):** 計算機入力に最適化されたテンキー・レイアウト。
* **Layer 1 (Mac Fn) / Layer 5 (Win Fn):** BLEプロファイルの切り替え、RGBアンダーグローのコントロール、各種メディアキー。
* **Layer 2 & 6 (Application):** 各種アプリケーション用ショートカット。
* **Layer 3 & 7 (Etc):** 拡張用自由定義レイヤー。

### Special Shortcuts (Combo)
OSのシームレスな切り替えをホームポジションを崩さずに行うため、コンボ入力を採用しています。
* **BSPC（Key 0） + \*（Key 4）の同時押し:** Mac環境とWindows環境のベースレイヤーを瞬時にトグル切り替え。

## Hardware Specification
* **Microcontroller:** Nordic nRF52840 (XIAO BLE)
* **Connectivity:** Bluetooth Low Energy & USB-C (充電・有線接続兼用)
* **Power:** リポバッテリー対応（物理電源スイッチによる安全なシャットダウン、過放電防止構造）
* **RGB Underglow:** SPIドライバ（SPI3）駆動による安定したライティングパフォーマンス。

## Design Inspiration
デザインはミニマルな美学、および機能美の極致であるインダストリアルデザインに深くインスパイアされています。

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
