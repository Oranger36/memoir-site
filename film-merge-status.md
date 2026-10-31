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
- GitHub Pages (`main` / `/`): hotel and airline walls use official logos plus names (airlines also show IATA).
- No 住过几次 / 飞过几次 / N 段 on the logo wall.
- Douban posters, book covers, and `assets/timeline.json` stay in place.
