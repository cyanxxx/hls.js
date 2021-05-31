- [x] 1.根据配置，~~清除 live~~(m3u8-parser:匹配 isSplitting, splittingReloadTime 加字段)
- [x] 2.改装 level detail（加 isSplitting 字段）
- [x] 3.baase-playlist(根据 splittingReloadTime 来设定重新加载 playlistLoaded 的时间)
- [x] 4.updateMediaElementDuration(若有 isSplitting，直接把 duration 赋值给 media)
- [x] 5.abort(onLevelLoaded 暂时好像没影响)
- [x] 6.audio-stream（onLevelLoaded 待观测）
- [x] 7.audio-track-stream（setAudioTrack 待观测）
- [x] 8.base-stream（\_streamEnded， getNextFragment， setStartPosition(不需要改变 startPosition)）
- [x] 9.buffer-control(updateMediaElementDuration 待观测)
      10.gap-control(poll 待观测)
- [x] 11.LatencyController（timeupdate 不需要更新 currtime）
- [x] 12.levelcontroller（set level 待观测）

- [x] 完成视频合并
- [x] 确认是否要待完成音频
