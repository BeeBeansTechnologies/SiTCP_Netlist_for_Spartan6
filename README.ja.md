Read this in other languages: [English](README.md), [日本語](README.ja.md)

# SiTCP Netlist for Spartan6

Xilinx Spartan 6用のSiTCP Netlist File(ngc file)です。


## SiTCP とは

物理学実験での大容量データ転送を目的としてFPGA（Field Programmable Gate Array）上に実装されたシンプルなTCP/IPです。

* SiTCPについては、[SiTCPライブラリページ](https://www.bbtech.co.jp/products/sitcp-library/)を参照してください。
* その他の関連プロジェクトは、[こちら](https://github.com/BeeBeansTechnologies)を参照してください。

![SiTCP](sitcp.png)


## 履歴

2010-08-10 Ver.4.0
* ARPに対する不具合が修正されました。

2010-12-14 Ver.4.1
* SiTCP送信バッファを32Kbyteから16Kbyteに変更しました。

2012-06-19 Ver.5.0
* 10BASE(10Mbps)動作時に誤動作するバグを修正しました。

2012-11-22 Ver.6.0
* SiTCPのクライアントモードを追加しました。

2012-11-26 Ver.7.0
* 受信時のACK応答方式の拡張を行いました。

2013-10-18 Ver.8.0
* IPGの最小値を3～15の範囲で設定可能にしました。

2016-02-09 Ver.9.0
* MACアドレス表示ポートを追加しました

2016-10-11 Ver.10.0
* 受信時のバグを修正しました

2017-05-29 Ver.11.0
* IEEE802.3xフローコントロール（PAUSE）に対応しました。
* クライアントモードでのARPリクエスト機能を追加しました。
* SiTCP_RSTのタイミングを変更しました（EEPROM設定値の転送完了まで延長）。
* データ受信時のACK送信形式を変更しました。
* MIF初期化機能を設定可能にしました。
