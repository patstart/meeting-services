# 基于Go的在线视频会议服务(开发中)

该项目是一个完全开源的在线视频会议服务，使用纯Go编写。包括SFU服务和会管服务，基于livekit/pion二次开发，提供了更丰富的会议功能，类似于腾讯会议。支持集群部署、双机热备、动态分辨率和视频多播。

## 特性

- **集群部署：** 支持可扩展和高可用的部署。
- **双机热备：** 确保高可用性和可靠性。
- **动态分辨率：** 根据网络条件调整视频质量。
- **视频多播：** 高效地将视频流传输给多个参与者。

## 计划功能

- **单个会议跨服：** 边缘接入以提高可扩展性。
- **跨系统会议：** 实现不同系统间的互操作性。
- **多种外部媒体接入：** 集成各种媒体来源。
- **本地录制：** 本地录制会议。
- **在线录制：** 服务器端录制会议。
- **电子白板：** 实时协作的互动白板。
- **媒体合成优化：** MCU集成以优化媒体处理。

## 安装

TODO

## 使用

* 配套客户端请参考[项目](https://github.com/patstart/meeting-client)

TODO

## 贡献

欢迎贡献！请提交pull request或打开issue讨论改进或修复。

## 许可证

本项目采用MIT许可证。