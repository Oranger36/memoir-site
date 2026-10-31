# 影视/书籍合并状态

## 本地片单 → 海报墙 — DONE
- 来源：`片单种子.md`（原 Movies/看过的电影）28 部
- `posters/`：既有封面未清空；复联2 `avengers-age-of-ultron.jpg` 已在

## 豆瓣导入 — DONE（2026-11-01）
- Profile：https://www.douban.com/people/135418632/ （刘成志）
- Export：`/workspace/memoir/douban-export.json`（movie 22 / book 2 / music 0）
- 影视墙：+22 部（与片单无重叠）→ 合计 **50**；封面 JPEG 已写入 `posters/`，`data-source="douban"`
- 书籍墙：+2（《万磁王2：翻转》《活着》）→ 合计 **65**；`book-covers/magneto-2-flip.jpg`、`to-live-yu-hua.jpg`
- 音乐：0（无变更）

## 其它已本地就绪（待推 live）
- `#timeline` + hotels/airlines logo 墙（见 assets/）
- Style：少字多图

## 部署
- GitHub Pages (`main` / `/`): this commit publishes the hotel and airline logo wall.
- Logo wall is brand marks + names (+ IATA only). No 住过几次 / 飞过几次 / N 段.
- `posters/`, `covers/`, and `book-covers/` were not deleted. Douban and 复联2 image files were not in the delta tarball, so those figures were not added and the existing walls stay as they were.
- `assets/timeline.json` was not in the delta. The timeline block stays hidden until that file is present.

## Hotels/Airlines logo wall (2026-11-01 02:10 Asia/Shanghai)
- Expanded hotels-airlines.json: 41 hotels (+3 weak), 18 brand logos, 14 airlines
- Official logos: Wikimedia/Wikipedia/Simple Icons (Marriott family, IHG, Shangri-La, Hilton, Cathay, HU/CZ/CA/3U/ZH/HX/9C/Y8/PN, etc.)
- Logo wall shows brand marks only — **no** 住过几次 / 飞过几次 / N段 counts
- Delta: `/workspace/memoir-site-delta.tar.gz`
