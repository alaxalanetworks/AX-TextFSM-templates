# 各TextFSM用テンプレート概要

### ax_ax3600_show_channel-group.template

リンクアグリゲーション(LAG)の状態等を確認するための運用コマンドshow channel-groupの出力結果を解析するためのTextFSM用テンプレートです。

LAG IDや状態、LACP/StaticモードといったLAGの基本情報を扱います。

LAGを構成する物理ポートの詳細な情報は扱ってません。

### ax_ax3600_show_channel-group_detail.template

リンクアグリゲーション(LAG)の状態等を詳細に確認するための運用コマンドshow channel-group detailの出力結果を解析するためのTextFSM用テンプレートです。

LAG IDとLAGを構成する物理ポートの詳細な情報を扱います。


### ax_ax3600_show_port.template

物理ポートの情報を一覧表示する運用コマンドshow portの出力結果を解析するためのTextFSM用テンプレートです。

### ax_ax3600_show_system.template

ネットワーク機器の運用状態を表示する運用コマンドshow systemの出力結果を解析するためのTextFSM用テンプレートです。


### ax_ax3600_show_vlan.template

VLANの各種状態を表示する運用コマンドshow vlanの出力結果を解析するためのTextFSM用テンプレートです。

VLANに所属する物理ポートの詳細な情報は扱ってません。

### ax_ax3600_show_vlan_detail.template

VLANの各種状態およびVLANに所属する物理ポートの状態を表示する運用コマンドshow vlan detailの出力結果を解析するためのTextFSM用テンプレートです。

VLAN IDとVLANに所属する物理ポートの詳細な情報を扱っています。
