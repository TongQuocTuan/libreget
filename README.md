<!--
Search keywords (kept here so GitHub search, Google and AI assistants can find the project):
LibreGet is a free open source downloader and media toolbox for Windows, macOS and Linux.
udemy downloader, hotmart downloader, kiwify downloader, course downloader, youtube downloader,
yt-dlp gui, instagram downloader, instagram story downloader, reels downloader, twitter downloader,
x video downloader, pinterest downloader, pinterest board backup, tiktok downloader, reddit downloader,
twitch vod downloader, bilibili downloader, telegram downloader, torrent client, magnet downloader,
subtitle downloader, whisper transcription, text to speech, epub reader, pdf reader, anki flashcards,
spaced repetition, music player, spicetify, media downloader, download manager, reddit thread archiver,
twitch chat downloader, twitch emotes, linkedin data export, spotify history, facebook album downloader,
pdf tools, pdf repair, pdf to markdown, image compressor, video compressor, video to gif, ctf tools,
mcp server, claude code plugin, tauri, rust, svelte.

GitHub allows 20 topics. The repository uses exactly these 20:
downloader, download-manager, media-downloader, video-downloader, youtube-downloader, yt-dlp,
yt-dlp-gui, course-downloader, udemy-downloader, hotmart-downloader, bilibili-downloader,
tiktok-downloader, instagram-downloader, twitter-downloader, reddit-downloader, telegram-downloader,
twitch-downloader, subtitle-downloader, epub-reader, spaced-repetition
-->

<p align="center">
  <img src="assets/readme/hero.png" alt="LibreGet: dán một liên kết, nhận về tập tin. Linh vật chim cánh cụt đưa các tập tin video, nhạc, PDF, hình ảnh, khóa học và torrent vào một thư mục. Khóa học, video, âm thanh, hình ảnh và torrent, rồi chuyển ngữ, chuyển đổi và quản lý." width="100%" />
</p>

<h1 align="center">LibreGet</h1>

<p align="center">
  <b>Tiếng Việt</b>
  · <a href="README.en.md">English</a>
  · <a href="README.ja.md">日本語</a>
  · <a href="README_pt_br.md">Português (BR)</a>
  · <a href="README.ru.md">Русский</a>
  · <a href="README_zh_CN.md">简体中文</a>
</p>

<p align="center">
  <b>Tải xuống khóa học Udemy và Hotmart, YouTube, Instagram, X, Pinterest, TikTok và hơn 1.800 trang web khác.<br/>Sau đó chuyển ngữ, chuyển đổi và quản lý những gì bạn đã lưu. Một ứng dụng máy tính miễn phí, không cần dùng terminal.</b>
</p>

<p align="center">
  <a href="https://github.com/TongQuocTuan/libreget/releases/latest"><img src="https://img.shields.io/github/v/release/TongQuocTuan/libreget?style=for-the-badge&label=release&color=F28500" alt="Latest release" /></a>
  <a href="https://github.com/TongQuocTuan/libreget/releases"><img src="https://img.shields.io/github/downloads/TongQuocTuan/libreget/total?style=for-the-badge&label=downloads&color=1E6FE8" alt="Total downloads" /></a>
  <a href="https://github.com/TongQuocTuan/libreget/stargazers"><img src="https://img.shields.io/github/stars/TongQuocTuan/libreget?style=for-the-badge&color=FFD426" alt="GitHub stars" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-GPL--3.0-2AA845?style=for-the-badge" alt="License GPL-3.0" /></a>
  <a href="https://hosted.weblate.org/engage/libreget/"><img src="https://hosted.weblate.org/widget/libreget/frontend/svg-badge.svg" alt="Translation status" /></a>
</p>

<p align="center">
  <a href="#tải-xuống-và-cài-đặt"><img src="https://img.shields.io/badge/Download_for_Windows,_macOS_or_Linux-→-F28500?style=for-the-badge" alt="Download LibreGet" height="40" /></a>
  &nbsp;
  <a href="#mục-tools-158-công-cụ-trong-25-danh-mục"><img src="https://img.shields.io/badge/See_the_158_tools-→-3D5BF0?style=for-the-badge" alt="See the Tools section" height="40" /></a>
</p>

<p align="center">
  <sub>Miễn phí. Mã nguồn mở theo giấy phép GPL-3.0. Không tài khoản, không quảng cáo, không thu thập dữ liệu về những gì bạn tải xuống. Tập tin của bạn ở lại trên máy tính của bạn.</sub>
</p>

<p align="center">
  <sub>Được duy trì bởi <a href="https://github.com/TongQuocTuan">TongQuocTuan</a> theo giấy phép GPL-3.0</sub>
</p>

<p align="center">
  <img src="assets/readme/home.png" alt="Màn hình chính của LibreGet: dán một URL, liên kết magnet hoặc tập tin .torrent và tập tin sẽ nằm trong thư mục của bạn" width="900" />
</p>

---

## Mục lục

- [Vì sao chọn LibreGet](#vì-sao-chọn-libreget)
- [Tải xuống và cài đặt](#tải-xuống-và-cài-đặt)
- [Lần tải đầu tiên trong một phút](#lần-tải-đầu-tiên-trong-một-phút)
- [LibreGet tải được những gì](#libreget-tải-được-những-gì)
- [Tiện ích mở rộng trình duyệt, từng bước](#tiện-ích-mở-rộng-trình-duyệt-từng-bước)
- [Mục Tools: 158 công cụ trong 25 danh mục](#mục-tools-158-công-cụ-trong-25-danh-mục)
- [LibreGet cho AI agent: máy chủ MCP và plugin Claude Code](#libreget-cho-ai-agent-máy-chủ-mcp-và-plugin-claude-code)
- [Plugin: Courses, Telegram, Convert](#plugin-courses-telegram-convert)
- [Mọi thứ khác trong hộp công cụ](#mọi-thứ-khác-trong-hộp-công-cụ)
- [Quyền riêng tư và những gì LibreGet từ chối làm](#quyền-riêng-tư-và-những-gì-libreget-từ-chối-làm)
- [Chính sách ký mã](#chính-sách-ký-mã)
- [Câu hỏi thường gặp](#câu-hỏi-thường-gặp)
- [Dòng lệnh](#dòng-lệnh)
- [Biên dịch từ mã nguồn](#biên-dịch-từ-mã-nguồn)
- [Đóng góp và bản dịch](#đóng-góp-và-bản-dịch)

---

## Vì sao chọn LibreGet

Bạn đã mua một khóa học và muốn lưu nó vào ổ đĩa trước khi nền tảng gỡ xuống. Bạn giữ một bảng mẹo yt-dlp vì các cờ lệnh chẳng bao giờ nhớ nổi. Bạn có một trang web cho Instagram stories, một trang khác cho video X, một tiện ích Chrome cho Pinterest, một đoạn mã Python cho phụ đề, và không thứ nào trong số đó nhớ lần đăng nhập của bạn.

LibreGet gom tất cả những thứ đó sau một ô nhập văn bản. Dán một liên kết, xem bản xem trước với các lựa chọn chất lượng, nhấn tải xuống. Cùng một cửa sổ đó sau đó phát khóa học, đọc PDF, chuyển ngữ âm thanh và sao lưu bảng Pinterest của bạn. yt-dlp và FFmpeg tự cài đặt và luôn được cập nhật, nên không có gì phải cấu hình và không cần mở terminal.

<p align="center">
  <img src="assets/readme/workflow.png" alt="Cách LibreGet hoạt động trong ba bước: dán một liên kết, LibreGet nhận diện trang web và chọn trình trích xuất gốc hoặc yt-dlp, tập tin nằm trong thư mục của bạn và mở trong trình phát tích hợp." width="100%" />
</p>

### So sánh với các công cụ khác

| | LibreGet | Chỉ dùng yt-dlp | Trang tải xuống cho một trang web | Trình tải khóa học trả phí |
|---|---|---|---|---|
| Trang web | Khóa học, Instagram, X, Pinterest, Bilibili, Telegram, torrent theo cơ chế gốc, cộng hơn 1.800 trang qua yt-dlp | Hơn 1.800 | Một | Một hoặc hai nền tảng |
| Cài đặt | Tải một tập tin, mở ra | Python, PATH, FFmpeg, cờ lệnh | Không cần | Trình cài đặt, khóa bản quyền |
| Nội dung cần đăng nhập | Cookie từ trình duyệt của bạn qua tiện ích mở rộng | Xuất `--cookies` thủ công | Hiếm khi | Đôi khi |
| Hàng đợi | Tiếp tục tải, thử lại với thời gian chờ tăng dần, quy tắc, kênh đang theo dõi | Một lệnh mỗi lần | Không | Tùy trường hợp |
| Sau khi tải | Trình phát, trình đọc, flashcard, ghi chú, 158 công cụ | Chỉ tập tin | Tập tin, thường bị mã hóa lại | Tập tin |
| Giá và giấy phép | Miễn phí, GPL-3.0 | Miễn phí, Unlicense | Miễn phí kèm quảng cáo | Thuê bao |

yt-dlp là bộ máy mà LibreGet chạy trên đó, và LibreGet sẽ không tồn tại nếu không có nó. Nếu bạn sống trong terminal và chỉ muốn lấy tập tin, chỉ dùng yt-dlp là công cụ phù hợp.

---

## Tải xuống và cài đặt

Chọn hệ thống của bạn. Mọi bản dựng đều được phát hành trên [trang Releases](https://github.com/TongQuocTuan/libreget/releases/latest). Các bản cập nhật đến ngay trong ứng dụng.

<table>
  <tr>
    <th align="left">Hệ thống</th>
    <th align="left">Tải gì</th>
    <th align="left">Cách khác</th>
  </tr>
  <tr>
    <td><b>Windows 10 / 11</b></td>
    <td><code>libreget_x.y.z_x64-setup.exe</code> (trình cài đặt)<br/><code>libreget_x.y.z_x64-portable.exe</code> (không cần cài đặt, chạy ở bất cứ đâu)<br/><code>libreget_x.y.z_x64_en-US.msi</code> (cho triển khai CNTT)</td>
    <td><code>winget install -e --id TongQuocTuan.LibreGet</code></td>
  </tr>
  <tr>
    <td><b>macOS 10.15+</b></td>
    <td><code>libreget_x.y.z_aarch64.dmg</code> cho Apple Silicon (M1 trở lên)<br/><code>libreget_x.y.z_x64.dmg</code> cho máy Mac Intel</td>
    <td><code>brew install --cask TongQuocTuan/tap/libreget</code></td>
  </tr>
  <tr>
    <td><b>Linux</b></td>
    <td><code>.deb</code> cho Debian và Ubuntu (amd64 và arm64)<br/><code>.rpm</code> cho Fedora, openSUSE và họ RHEL (x86_64 và aarch64)<br/><code>.AppImage</code> cho mọi trường hợp còn lại (amd64 và aarch64)</td>
    <td>AppImage tự cập nhật qua các tập tin <code>.zsync</code></td>
  </tr>
</table>

### Cảnh báo ở lần khởi chạy đầu tiên, và cách xử lý

LibreGet không được ký bằng chứng chỉ trả phí, nên mỗi hệ thống đều hiện cảnh báo ở lần đầu tiên. Đây là chuyện bình thường với các ứng dụng máy tính mã nguồn mở và bạn chỉ cần xử lý một lần.

**Windows.** SmartScreen hiện một hộp màu xanh. Nhấn **More info**, rồi **Run anyway**.

**macOS.** Gatekeeper từ chối mở ứng dụng và có thể báo là ứng dụng "bị hỏng". Sau khi bạn kéo LibreGet vào Applications, mở Terminal (Spotlight, gõ "Terminal") và dán hai dòng này:

```bash
xattr -cr /Applications/libreget.app
codesign --force --deep --sign - /Applications/libreget.app
```

Sau đó mở LibreGet từ Launchpad như bình thường.

**Linux, AppImage trên Debian 12+ hoặc Ubuntu 24.04+.** Các bản phát hành này không kèm FUSE 2, thứ mà AppImage cần. Nếu tập tin báo lỗi libfuse, chạy `sudo apt install libfuse2`, hoặc khởi chạy bằng `./libreget.AppImage --appimage-extract-and-run`. Gói `.deb` tránh được chuyện này hoàn toàn.

### Plugin đa phương tiện trên Linux

LibreGet vẽ cửa sổ của nó bằng WebKitGTK, và WebKitGTK phát mọi `<video>` và `<audio>` qua GStreamer. Nếu thiếu plugin GStreamer, WebKitGTK không âm thầm bỏ qua phần đa phương tiện: nó tự hủy tiến trình web của mình ngay khi một trình phát xuất hiện, và bạn chỉ còn lại một cửa sổ trống. Hầu hết bản phân phối cho máy tính để bàn đã có sẵn các plugin này. Arch và các bản ảnh máy chủ tối giản coi chúng là tùy chọn, nên hãy cài đặt một lần:

```bash
sudo apt install gstreamer1.0-plugins-good gstreamer1.0-plugins-bad gstreamer1.0-libav   # Debian, Ubuntu
sudo dnf install gstreamer1-plugins-good gstreamer1-plugins-bad-free gstreamer1-plugin-libav   # Fedora
sudo pacman -S gst-plugins-good gst-plugins-bad gst-libav   # Arch
```

`gstreamer1.0-plugins-good` (`gst-plugins-good`) là gói ngăn được sự cố, vì bộ phận xuất âm thanh mà WebKitGTK nhất quyết cần nằm ở đó. Hai gói còn lại mang bộ giải mã H.264 và AAC, nên nếu thiếu chúng thì trình phát vẫn mở nhưng im lặng hoặc đen màn hình. Gói `.deb` và `.rpm` yêu cầu cả ba gói, nên chuyện này chỉ xảy ra với AppImage hoặc gói tự biên dịch thủ công.

### Chế độ portable

Tạo một tập tin trống tên `portable.txt` (hoặc `.portable`) ngay cạnh tập tin `.exe` trên Windows rồi khởi chạy lại. Cài đặt, cơ sở dữ liệu, cookie, plugin, bộ nhớ đệm, yt-dlp và FFmpeg đều chuyển sang thư mục `data` ngay cạnh tập tin thực thi. Không thứ gì chạm vào `AppData`, nên toàn bộ bản cài vừa trong một chiếc USB.

---

## Lần tải đầu tiên trong một phút

1. Mở LibreGet. Màn hình thiết lập hỏi ngôn ngữ và giao diện của bạn, rồi cài đặt yt-dlp và FFmpeg chỉ bằng một cú nhấp. yt-dlp được kiểm tra theo SHA-256 trước khi chạy.
2. Sao chép bất kỳ liên kết nào: một video YouTube, một reel Instagram, một bài đăng X, một bảng Pinterest, một magnet, một URL tập tin trực tiếp.
3. Dán nó vào ô trên màn hình chính. LibreGet nhận diện trang web và hiện tiêu đề, ảnh thu nhỏ cùng các chất lượng có sẵn. Chọn một chất lượng rồi nhấn Enter.

Trang Downloads hiện tốc độ, giai đoạn và thời gian ước tính đọc trực tiếp từ trình tải xuống, nên một lượt tải bị kẹt trông đúng là bị kẹt thay vì đứng yên ở "còn 3 giây". Các lượt tải bị ngắt sẽ tiếp tục từ chỗ đã dừng. Những trang giới hạn tốc độ được thử lại với thời gian chờ tăng dần, và số kết nối trên mỗi trang tự điều chỉnh, nên YouTube nhận tới 16 đoạn tải song song trong khi một trang trả về 429 thì nhận ít hơn. Khi máy có Python 3.10 trở lên, yt-dlp chạy dưới dạng zipapp trên đó và khởi động trong chưa đầy một giây thay vì giải nén tập tin nhị phân đi kèm mỗi lần khởi chạy.

<p align="center">
  <img src="assets/readme/downloads.png" alt="Trang Downloads của LibreGet với một lượt tải YouTube 4K đang chạy, hiện giai đoạn, tốc độ, thời gian ước tính và chính xác lệnh yt-dlp, cùng các mục đang xếp hàng và đã hoàn thành" width="900" />
</p>

### Bỏ qua cửa sổ hoàn toàn

Sao chép một liên kết ở bất cứ đâu trên hệ thống rồi nhấn **Ctrl+Shift+D** (**Cmd+Shift+D** trên macOS). LibreGet đọc clipboard và bắt đầu tải xuống ở chế độ nền. Một phím tắt thứ hai, **Ctrl+Shift+M**, chỉ lấy âm thanh, nên một liên kết YouTube trở thành MP3 mà không cần mở gì cả. Tính năng này tắt cho đến khi bạn bật lên, và cả hai phím tắt đều có thể gán lại trong **Settings → Downloads → Clipboard & hotkeys**.

---

## LibreGet tải được những gì

LibreGet có trình trích xuất gốc cho các nền tảng mọi người dùng nhiều nhất, và giao mọi thứ còn lại cho [yt-dlp](https://github.com/yt-dlp/yt-dlp), vốn bao phủ khoảng 1.800 trang web.

| Danh mục | Trang web và định dạng |
|---|---|
| <img src="https://api.iconify.design/ph/graduation-cap.svg?color=%23F28500" width="18" height="18" align="center" alt="Online courses" /> Khóa học trực tuyến | 38 nền tảng được hỗ trợ (Hotmart, Udemy, Kiwify, Rocketseat, Coursera, Domestika, Skillshare và nhiều nền tảng khác) qua plugin Courses tích hợp sẵn. Mọi bài học, lựa chọn mục, tập tin đính kèm, tiếp tục từ chỗ bạn đã dừng. |
| <img src="https://api.iconify.design/ph/film-slate.svg?color=%238E3FD8" width="18" height="18" align="center" alt="Video and audio" /> Video và âm thanh | YouTube (video, danh sách phát, kênh, phát trực tiếp từ đầu, chương, SponsorBlock), Instagram, TikTok, X/Twitter, Reddit, Twitch (VOD, clip, phát trực tiếp), Vimeo, Bluesky, Threads, Pinterest, Douyin |
| <img src="https://cdn.simpleicons.org/bilibili/00A1D6" width="18" height="18" align="center" alt="Bilibili" /> Bilibili, đã đăng nhập | 4K, HDR, Dolby Vision, Hi-Res lossless và Dolby Atmos tùy theo gói đăng ký của bạn. Bình luận danmaku dưới dạng XML, ASS hoặc JSON, tập tin NFO cho Kodi và Jellyfin, mẫu đặt tên tùy chỉnh, 11 loại URL gồm bangumi, khóa học, mục yêu thích, xem sau và lịch sử |
| <img src="https://api.iconify.design/ph/images.svg?color=%23E0A800" width="18" height="18" align="center" alt="Image galleries" /> Thư viện ảnh | Toàn bộ thư viện và hồ sơ từ hơn 250 trang web qua gallery-dl (DeviantArt, Pixiv, ArtStation, Flickr, Tumblr, Imgur, Kemono và nhiều trang khác) |
| <img src="https://api.iconify.design/ph/stack.svg?color=%23FFB340" width="18" height="18" align="center" alt="Bulk" /> Tải hàng loạt | Dán nhiều liên kết hoặc nạp một tập tin `.txt`, tải toàn bộ subreddit, hồ sơ Reddit và X, hồ sơ Instagram và Pinterest, album Facebook |
| <img src="https://api.iconify.design/ph/folder-simple.svg?color=%23A66A24" width="18" height="18" align="center" alt="Files and transfer" /> Tập tin và truyền tải | Tập tin `.torrent` và liên kết magnet với trình khách BitTorrent tích hợp, tập tin HTTP trực tiếp, danh sách phát HLS và DASH, và truyền tải trực tiếp giữa hai máy cài LibreGet bằng một mã từ ngắn |
| <img src="https://cdn.simpleicons.org/telegram/2CA5E0" width="18" height="18" align="center" alt="Telegram" /> Telegram | Ảnh, video, tập tin và âm thanh từ bất kỳ kênh hoặc nhóm nào bạn tham gia, được lưu vào các thư mục kênh có tổ chức (`LibreGram/<channel>/`), qua plugin Telegram tích hợp sẵn |

Các tùy chọn bạn đặt một lần rồi quên: chất lượng mặc định, định dạng chỉ lấy âm thanh (MP3, M4A, Opus, FLAC hoặc WAV), ngôn ngữ và định dạng phụ đề (SRT, VTT, ASS, nhúng hoặc tập tin riêng), nhúng ảnh thu nhỏ và siêu dữ liệu, mẫu tên tập tin, sắp xếp theo nền tảng, bỏ qua tập tin đã có, tách theo chương, giới hạn tốc độ, số lượt tải đồng thời, proxy. Các quy tắc đưa một kênh hoặc máy chủ nhất định vào thư mục và chất lượng bạn chọn mà không hỏi lại. Các kênh đang theo dõi được kiểm tra ở chế độ nền và có thể tự động tải các nội dung mới đăng kèm thông báo trên khay hệ thống.

<p align="center">
  <img src="assets/readme/settings.png" alt="Cài đặt của LibreGet: thanh bên nhóm theo Appearance, Downloads, Network, Cookies, Channels, AI, Plugins và Advanced, và mục tải xuống với Output, Quality, Subtitles, Clipboard và hotkeys, Per-platform options" width="900" />
</p>

---

## Tiện ích mở rộng trình duyệt, từng bước

Tiện ích mở rộng làm hai việc. Trên các trang web mà nó nhận biết (YouTube, Instagram, TikTok, X, Reddit, Twitch, Pinterest, Bluesky, Telegram, Vimeo, Udemy, Hotmart, Rocketseat, Bilibili, SoundCloud), nó gửi trang đó tới LibreGet chỉ bằng một cú nhấp hoặc bằng **Alt+O**. Trên bất kỳ trang nào khác, nó theo dõi lưu lượng mạng để tìm các luồng MP4, HLS, DASH, WebM và âm thanh rồi liệt kê chúng trong cửa sổ bật lên. Trong cả hai trường hợp, nó chuyển tiếp cookie và referer của bạn, và chính điều đó giúp LibreGet tải được nội dung riêng tư mà bạn đã đăng nhập, chẳng hạn Instagram stories, một khóa học trả phí hay một video chỉ dành cho thành viên. Cookie được nhóm theo từng trang web thật, nên một tên miền `.com.br` của Brazil có mục riêng thay vì dùng chung với mọi tên miền `.com.br` khác. Cửa sổ bật lên còn có công tắc **Force H.264** cho YouTube, dành cho các máy bị giật khi chạy VP9 và AV1.

Với những trang web mà trình dò tìm không nhìn thấy, có **Deep search**, một công tắc trong cửa sổ bật lên sẽ móc vào chính trình phát video của trang và bắt được các danh sách phát không bao giờ xuất hiện dưới dạng yêu cầu mạng. Nó xin quyền trên mọi trang web ở lần đầu tiên và vẫn tắt cho đến lúc đó. Xung quanh nó, trình dò tìm ước tính dung lượng của một luồng HLS trước khi bạn tải xuống, ghép cặp các track video và âm thanh riêng biệt mà trang web phục vụ để bạn nhận được một tập tin duy nhất, kiểm tra những byte đầu tiên của thứ nó tìm được để một trang lỗi HTML không bao giờ bị lưu thành video, và cho phép bạn sửa các quy tắc bắt luồng trong trang tùy chọn. Cũng chính trang tùy chọn đó có thể sao lưu danh sách tiện ích bạn đã cài, đề phòng Chrome loại bỏ các tiện ích Manifest V2; việc đó cần quyền "management" tùy chọn và chỉ xin khi bạn dùng đến.

Mã nguồn của tiện ích mở rộng trình duyệt đi kèm và các bản phát hành độc lập được duy trì tại [TongQuocTuan/libreget-extension](https://github.com/TongQuocTuan/libreget-extension). Hãy chọn mức phù hợp với mức độ thoải mái của bạn.

<p align="center">
  <img src="assets/readme/extension.png" alt="Linh vật chim cánh cụt cắm một sợi cáp từ cửa sổ trình duyệt vào cửa sổ ứng dụng LibreGet, cookie di chuyển dọc theo cáp cùng một ổ khóa và một ngôi nhà phía trên: việc ghép nối ở lại trên máy của bạn." width="100%" />
</p>

### Mức 1: từ trong ứng dụng (không cần tải xuống, không cần tập tin zip)

1. Mở LibreGet và cài đặt nếu bạn chưa cài. Khởi chạy một lần.
2. Vào **Settings → Plugins → Browser extension**. Nhấn **Update / Install** cạnh Chrome. LibreGet sao chép tiện ích đi kèm trong nó vào một thư mục rồi mở thư mục đó cho bạn.
3. Mở Chrome (Edge, Brave và các trình duyệt Chromium khác cũng tương tự) rồi gõ `chrome://extensions` trên thanh địa chỉ.
4. Bật **Developer mode** bằng công tắc ở góc trên bên phải.
5. Nhấn **Load unpacked** và chọn thư mục LibreGet vừa mở.
6. Biểu tượng LibreGet xuất hiện trên thanh công cụ. Một trang tùy chọn tự mở và báo rằng nó đang tìm ứng dụng.
7. Quay lại LibreGet, vẫn ở **Settings → Plugins → Browser extension**, nhấn **Pair extension**. Trong vài giây, ứng dụng báo "Extension connected" và trang tùy chọn chuyển sang màu xanh. Xong.

Từ giờ trở đi, hãy truy cập bất kỳ trang được hỗ trợ nào rồi nhấn vào biểu tượng. Trang đó, cookie của nó và tiêu đề của nó được gửi tới LibreGet và lượt tải bắt đầu. Cookie của bạn cũng xuất hiện trong **Settings → Cookies**, nơi plugin Courses và các công cụ Instagram, X và Pinterest dùng lại chúng.

### Mức 2: từ tập tin zip của bản phát hành

Mỗi bản phát hành đều kèm các tập tin nén tiện ích đã biên dịch sẵn. Tải `libreget-chrome-extension.zip` hoặc `libreget-firefox-extension.zip` từ trang [TongQuocTuan/libreget-extension releases](https://github.com/TongQuocTuan/libreget-extension/releases/latest) chính thức, giải nén, rồi làm theo các bước 3 đến 7 ở trên và trỏ **Load unpacked** vào thư mục đã giải nén. Dùng cách này nếu bạn giữ ứng dụng trên một máy và trình duyệt trên một máy khác, hoặc nếu bạn đang cài đặt cho người khác.

### Mức 3: Firefox, các trình duyệt khác và ghép nối thủ công

Firefox: cài đặt trực tiếp từ Mozilla Add-ons (đang chờ AMO phê duyệt) hoặc tải `libreget-firefox-extension.zip` từ [libreget-extension releases](https://github.com/TongQuocTuan/libreget-extension/releases/latest). Để thử tạm thời: **Settings → Plugins → Browser extension → Update / Install** cạnh Firefox, rồi mở `about:debugging#/runtime/this-firefox`, nhấn **Load Temporary Add-on** và chọn `manifest.json` trong thư mục đã xuất. Safari chưa được hỗ trợ vì tiện ích Safari phải phát hành qua App Store.

Ghép nối thủ công: nếu **Pair extension** hết thời gian chờ, mở trang tùy chọn của tiện ích (nhấn chuột phải vào biểu tượng → Options), rồi trong LibreGet hiện và sao chép **Pairing token** rồi dán vào trang tùy chọn. URL của điểm cuối được phát hiện tự động. Ứng dụng lắng nghe trên `127.0.0.1` các cổng 47720 đến 47729 và mã token được tạo riêng cho mỗi bản cài, nên không thứ gì rời khỏi máy của bạn.

Nếu tiện ích đã cài nhưng LibreGet đang đóng, các cú nhấp sẽ dùng dự phòng là lược đồ liên kết `libreget://`, vẫn xếp hàng URL nhưng không thể mang theo cookie. Hãy tích "Always allow" ở lần đầu Chrome hỏi.

---

## Mục Tools: 158 công cụ trong 25 danh mục

Tools là phần của LibreGet đã phát triển vượt khỏi việc tải xuống. Mỗi ô là một công việc: một lệnh Rust độc lập với JSON vào và JSON ra, và cũng chính điều đó giúp các AI agent điều khiển chúng qua máy chủ MCP tích hợp sẵn. Trung tâm có một ô tìm kiếm hiểu cả tiếng Anh và tiếng Bồ Đào Nha ("legenda" tìm ra các công cụ phụ đề) và một bộ lọc nền tảng, còn các công cụ chỉ chạy trên Windows thì ghi rõ trên ô và ẩn đi ở nơi khác. Mọi thứ dưới đây đều chạy trên máy của bạn; chỉ những công cụ nào lấy dữ liệu từ trang web mang tên chúng mới chạm tới mạng.

<p align="center">
  <img src="assets/readme/illustration-tools.png" alt="Linh vật chim cánh cụt mở một hộp dụng cụ đầy các ô công cụ: micro, phụ đề, kéo, PDF, ảnh, bánh răng, thư mục, nam châm, điện thoại, AI, nhạc, quả địa cầu, bàn phím, trò chuyện và cờ lê" width="900" />
</p>

<p align="center">
  <img src="assets/readme/tools.png" alt="Trung tâm Tools của LibreGet với 25 danh mục: YouTube, Speech and subtitles, Video editing, Audio, Instagram, X, Facebook, Reddit, Pinterest, Twitch, Bilibili, Spotify, Music, LinkedIn, Games, PDF, Documents, Images, System, Files, Downloads, Automation, Phone, AI và CTF and analysis" width="900" />
</p>

Chú giải trạng thái: không có dấu nghĩa là đã sẵn sàng, **beta** nghĩa là đã hoạt động nhưng chưa được kiểm tra với mọi loại tài khoản, **planned** nghĩa là ô đã có để bạn thấy hướng phát triển và hiện chưa làm gì cả.

<table>
  <tr>
    <td><img src="assets/readme/tools-instagram.png" alt="Các công cụ Instagram trong LibreGet: tải bài đăng, tải hàng loạt, âm thanh reel, stories, highlights, người xem story, xem hồ sơ, ảnh đại diện HD, tải hồ sơ, người không theo dõi lại, người hâm mộ, theo dõi lẫn nhau, ai đã bỏ theo dõi, người theo dõi ma, danh sách trắng, xuất dữ liệu, phân tích, so sánh hồ sơ, khám phá hashtag, bình luận, người đã thích, chọn người trúng giveaway, đăng bài và lên lịch" /></td>
    <td><img src="assets/readme/tools-x.png" alt="Các công cụ X / Twitter trong LibreGet: tải bài đăng, mở toàn bộ thread, bài đăng thành ảnh, X-ray hồ sơ, media của hồ sơ, tìm kiếm nâng cao, xuất bookmark, ai không theo dõi lại, kho lưu trữ X của bạn và Grok" /></td>
  </tr>
  <tr>
    <td><img src="assets/readme/tools-pinterest.png" alt="Các công cụ Pinterest trong LibreGet: tải pin, sao lưu bảng, sao lưu hồ sơ, tìm kiếm không AI hay quảng cáo, pin tương tự, tìm nguồn, trùng lặp, bảng màu, thư viện ngoại tuyến và gợi ý từ khóa" /></td>
    <td><img src="assets/readme/tools-pdf.png" alt="Các công cụ PDF trong LibreGet: gộp, tách, nén, chuyển đổi, OCR, sửa chữa, mật khẩu và quyền, watermark và đánh số, cắt lề, mục lục, kiểm tra che mờ, PDF an toàn và PDF sang Markdown" /></td>
  </tr>
  <tr>
    <td><img src="assets/readme/tools-linkedin.png" alt="Các công cụ LinkedIn trong LibreGet: tổng quan dữ liệu, kết nối, tin nhắn và điểm hồ sơ, tất cả đọc từ bản xuất dữ liệu chính thức" /></td>
    <td><img src="assets/readme/tools-ctf.png" alt="Các công cụ CTF và phân tích trong LibreGet: hash và HMAC, đây là tập tin gì, mật mã cổ điển, XOR, mã hóa và phân tích tần suất" /></td>
  </tr>
</table>

### <img src="https://cdn.simpleicons.org/youtube/FF0000" width="20" height="20" align="center" alt="YouTube" /> YouTube (11)

- **Tải video.** Dán một liên kết rồi chọn chất lượng, định dạng và phụ đề. Cùng bộ máy với màn hình chính.
- **Siêu dữ liệu.** Lưu thông tin, mô tả và ảnh thu nhỏ mà không cần video.
- **Ảnh thu nhỏ.** Duyệt mọi ảnh bìa và lưu ở bất kỳ độ phân giải nào.
- **Phụ đề.** Tải phụ đề, hoặc gộp hai ngôn ngữ thành một tập tin song ngữ.
- **Bình luận và chương.** Lấy bình luận hoặc dấu chương, lọc chúng, xuất JSON hoặc CSV.
- **Trò chuyện trực tiếp.** Lưu lại bản phát lại trò chuyện của một buổi phát trực tiếp dưới dạng JSON hoặc CSV.
- **Xưởng phụ đề.** Sửa, dịch và căn lại thời gian cho các tập tin SRT, VTT và ASS với dạng sóng, đồng bộ hai điểm, tìm và thay thế, sửa tự động, cùng ngữ pháp và dịch thuật bằng AI.
- **SponsorBlock.** Xem các đoạn tài trợ, mở đầu và kết thúc rồi lấy cờ yt-dlp để bỏ qua chúng.
- **Lượt không thích.** Lượt thích, lượt không thích và xếp hạng từ Return YouTube Dislike.
- **Ảnh thu nhỏ thật.** Các khung hình mà CDN đã có ở 25, 50 và 75 phần trăm, thay cho ảnh bìa câu view.
- **Buộc dùng H.264.** Một công tắc trong tiện ích trình duyệt giữ YouTube ở H.264 thay vì VP9 và AV1, cho những máy bị giật với codec mới hơn.

### <img src="https://api.iconify.design/ph/waveform.svg?color=%23FF5E7A" width="20" height="20" align="center" alt="Speech and subtitles" /> Giọng nói và phụ đề (8)

- **Chuyển ngữ.** Âm thanh hoặc video thành phụ đề bằng whisper.cpp, ngoại tuyến. Các mô hình tải theo nhu cầu, tăng tốc Metal trên macOS.
- **Chuyển văn bản thành giọng nói.** Giọng tự nhiên từ Microsoft Edge, miễn phí, kèm tập tin phụ đề đồng bộ.
- **Dịch phụ đề.** Dịch một tập tin SRT bằng nhà cung cấp AI của bạn hoặc một máy chủ LibreTranslate, giữ nguyên thời gian.
- **Lồng tiếng từ phụ đề.** Biến một tập tin SRT thành track giọng nói khớp với từng dòng và tùy chọn thay thế âm thanh của video. *beta*
- **Nhân bản giọng nói**, **Thiết kế giọng nói** và **Tách giọng hát** qua một bản cài VoiceStudio chạy trên máy của bạn. *beta*
- **Đọc chính tả.** Nhấn một phím tắt toàn cục, nói, và whisper gõ văn bản vào vị trí con trỏ của bạn. *beta*

### <img src="https://api.iconify.design/ph/film-slate.svg?color=%238E3FD8" width="20" height="20" align="center" alt="Video editing" /> Chỉnh sửa video (14)

- **Cắt một đoạn clip.** Chọn một video trên ổ đĩa và cắt ra một đoạn. Kết quả nằm trong hàng đợi tải xuống.
- **Chuyển đổi.** Đổi định dạng chứa, codec hoặc độ phân giải, hoặc nén, qua plugin Convert.
- **Nén tới một dung lượng.** Đạt đúng mục tiêu, 10 MB cho Discord hoặc 25 MB cho e-mail, bằng mã hóa hai lượt.
- **Video thành GIF.** Một đoạn clip thành GIF hoặc WebP động, với bảng màu không bị xỉn.
- **Cắt khoảng lặng.** Tìm khoảng lặng trong một bản ghi rồi cắt khỏi cả hình và tiếng cùng lúc.
- **Chuyển đổi phụ đề.** SRT, VTT và ASS qua lại với nhau, hoặc đốt một phụ đề vào hình ảnh.
- **Đồng bộ lại phụ đề.** Chậm, sớm hay trôi dần: dịch chuyển nó, kéo giãn cho một tốc độ khung hình khác, hoặc sửa bằng hai điểm neo.
- **Khôi phục video.** Loại bỏ nhấp nháy, nhiễu hạt và dải màu bằng các bộ lọc mà FFmpeg đã có sẵn.
- **Ổn định video.** vidstab hai lượt: đo độ rung trên toàn bộ clip, rồi triệt tiêu nó.
- **Ảnh thành sticker.** Một bức ảnh hoặc một đoạn clip thành sticker WhatsApp hoặc Telegram vừa đúng giới hạn kích thước.
- **Phụ đề tự động** và **Chuyển văn bản thành giọng nói** mở các công cụ giọng nói ở trên.
- **Quay màn hình.** Màn hình và âm thanh hệ thống qua FFmpeg, với bộ đệm phát lại lưu lại những gì vừa xảy ra. *beta*
- **Trình sửa timeline.** *planned*

### <img src="https://api.iconify.design/ph/speaker-high.svg?color=%23E0203F" width="20" height="20" align="center" alt="Audio" /> Âm thanh (2)

- **Chuẩn hóa độ lớn.** EBU R128 hai lượt, để âm thanh đạt mức mà phát trực tuyến, podcast hay phát sóng mong đợi.
- **Khử nhiễu.** Tiếng rít, tiếng quạt và tiếng ồn phòng được lấy ra khỏi bản ghi, không cần tải gì thêm.

### <img src="https://cdn.simpleicons.org/instagram/E4405F" width="20" height="20" align="center" alt="Instagram" /> Instagram (24)

Tất cả các công cụ này chạy trên phiên Instagram của chính bạn do tiện ích trình duyệt ghi lại, nên stories, bạn thân và danh sách của bạn đều hoạt động. Các lần đọc được giãn nhịp và các hành động ghi sẽ dừng ngay khi có dấu hiệu đầu tiên của giới hạn tốc độ.

- **Tải bài đăng.** Ảnh, video, reel, IGTV hoặc carousel từ một liên kết, chất lượng tốt nhất.
- **Tải nhiều liên kết.** Dán một danh sách hoặc một tập tin `.txt` rồi nhận tất cả.
- **Âm thanh reel.** Chỉ giữ lại âm thanh, dưới dạng M4A hoặc MP3.
- **Stories.** Tải stories, kể cả bạn thân, mà không bị đánh dấu là đã xem.
- **Highlights.** Một highlight hoặc mọi highlight của một hồ sơ.
- **Ai đã xem story của tôi.** Liệt kê và xuất người xem của từng story đang hoạt động.
- **Xem hồ sơ.** Tiểu sử, số liệu, ảnh HD và việc tài khoản có theo dõi bạn không.
- **Ảnh hồ sơ HD.**
- **Tải một hồ sơ.** Mọi bài đăng, reel, bài được gắn thẻ hoặc đã lưu, với giới hạn do bạn chọn.
- **Ai không theo dõi lại.** So sánh người theo dõi và đang theo dõi, bảo vệ tài khoản bằng danh sách trắng, bỏ theo dõi với nhịp độ an toàn.
- **Người hâm mộ.** Các tài khoản theo dõi bạn nhưng bạn không theo dõi lại, với tùy chọn gỡ họ.
- **Theo dõi lẫn nhau.**
- **Ai đã bỏ theo dõi tôi.** Ảnh chụp nhanh các danh sách của bạn theo thời gian cho thấy ai đã rời đi và ai mới đến.
- **Người theo dõi ma.** Những người theo dõi không bao giờ thích hay bình luận, và những người tương tác nhiều nhất.
- **Danh sách trắng.** Các tài khoản không bao giờ được gợi ý bỏ theo dõi.
- **Xuất dữ liệu.** Đọc tập tin zip "Download your information" của Meta ngoại tuyến: yêu cầu đang chờ, bạn thân, đã chặn và nhiều hơn nữa.
- **Phân tích hồ sơ.** Tỷ lệ tương tác, nhịp độ, ngày và giờ tốt nhất, hashtag và bài đăng hàng đầu của bất kỳ hồ sơ công khai nào.
- **So sánh hồ sơ.** Tối đa sáu hồ sơ đặt cạnh nhau.
- **Khám phá hashtag.** Số lượng bài đăng, bài gần đây và bài hàng đầu, hashtag liên quan, tải xuống.
- **Xuất bình luận.** Mọi bình luận của một bài đăng dưới dạng CSV, có bộ lọc.
- **Ai đã thích.** Liệt kê và xuất các tài khoản đã thích một bài đăng.
- **Chọn người trúng giveaway.** Rút thăm người chiến thắng trong số các bình luận với quy tắc về nhắc tên, từ khóa và một lượt tham gia mỗi người.
- **Đăng bài.** Ảnh, carousel, reel, video hoặc story qua phiên của bạn hoặc Graph API chính thức. *beta*
- **Lên lịch đăng bài.** Xếp hàng các bài đăng cho một ngày giờ, LibreGet đăng chúng trong khi đang mở. *beta*

### <img src="https://cdn.simpleicons.org/x/000000/ffffff" width="20" height="20" align="center" alt="X" /> X / Twitter (10)

Dữ liệu công khai đi qua API FxTwitter mà không cần đăng nhập. Bất cứ thứ gì riêng tư (bookmark, danh sách theo dõi của bạn, Grok trên X) đều dùng phiên X của bạn từ trình quản lý cookie.

- **Tải bài đăng.** Video, ảnh và GIF từ bất kỳ bài đăng nào.
- **Mở toàn bộ thread.** Toàn bộ thread trên một trang, xuất dưới dạng Markdown, HTML hoặc văn bản.
- **Bài đăng thành ảnh.** Một thẻ PNG gọn gàng của một bài đăng để chia sẻ ở bất cứ đâu.
- **X-ray hồ sơ.** Mức tương tác, thời điểm đăng tốt nhất, bài đăng và hashtag hàng đầu của bất kỳ tài khoản nào.
- **Media của hồ sơ.** Mọi ảnh và video từ một hồ sơ, chất lượng gốc, trong một lần.
- **Tìm kiếm nâng cao.** Xây dựng truy vấn bằng toán tử X, xem xu hướng, xuất kết quả.
- **Xuất bookmark.** Mọi bookmark kèm thư mục, sang JSON, CSV, Markdown hoặc HTML. *beta*
- **Ai không theo dõi lại.** Kiểm tra đang theo dõi so với người theo dõi rồi bỏ theo dõi an toàn với danh sách trắng. *beta*
- **Kho lưu trữ X của bạn.** Mở tập tin zip dữ liệu ngoại tuyến: thống kê, bài đăng hàng đầu, lượt thích và danh sách theo dõi.
- **Grok.** Hỏi Grok với tìm kiếm X trực tiếp hoặc tóm tắt một thread, qua API xAI hoặc phiên X của bạn. *beta*

### <img src="https://cdn.simpleicons.org/facebook/1877F2" width="20" height="20" align="center" alt="Facebook" /> Facebook (2)

- **Tải album.** Dán một liên kết album và mọi ảnh và video bên trong sẽ nằm trong một thư mục.
- **Tải video.** Một video hoặc reel, ngay từ ô nhập liên kết.

### <img src="https://cdn.simpleicons.org/reddit/FF4500" width="20" height="20" align="center" alt="Reddit" /> Reddit (3)

- **Tải bài đăng.** Video có tiếng từ v.redd.it, thư viện ảnh, ảnh đơn và liên kết ngoài.
- **Lưu trữ thread.** Bài đăng và mọi bình luận dưới dạng Markdown, một trang HTML có thể duyệt và JSON thô, trong khi chúng vẫn còn đó.
- **Đọc bản xuất dữ liệu của tôi.** Tập tin zip dữ liệu chính thức của Reddit được biến thành bản tóm tắt mà bạn thực sự đọc được.

### <img src="https://cdn.simpleicons.org/pinterest/BD081C" width="20" height="20" align="center" alt="Pinterest" /> Pinterest (10)

Hoạt động không cần đăng nhập với bất cứ thứ gì công khai. Cookie chỉ cần cho bảng bí mật và cho việc bỏ lưu.

- **Tải pin.** Ảnh với chất lượng gốc, video dưới dạng MP4, GIF, carousel hoặc trang story.
- **Sao lưu bảng.** Mọi pin của một bảng hoặc mục với bản gốc, video, CSV/JSON và đồng bộ tăng dần.
- **Sao lưu hồ sơ.** Mọi bảng công khai của một hồ sơ, một thư mục cho mỗi bảng, cộng các pin đã tạo.
- **Tìm kiếm không AI hay quảng cáo.** Bộ lọc ẩn ảnh AI, pin quảng cáo và video, rồi tải xuống.
- **Pin tương tự.** Mục "More like this" của bất kỳ pin nào, có thể lọc và tải xuống.
- **Tìm nguồn.** Liên kết đích, tác giả, kiểm tra liên kết chết, Wayback Machine và tìm kiếm hình ảnh ngược.
- **Pin trùng trong một bảng.** Các pin giống hệt và gần giống hệt, với tùy chọn bỏ lưu.
- **Bảng màu.** Bảng màu của một bảng hoặc pin dưới dạng hex, CSS hoặc JSON.
- **Thư viện ngoại tuyến, PDF, CSV.** Một bảng dưới dạng thư viện HTML có thể tìm kiếm, một moodboard PDF hoặc một bảng tính.
- **Gợi ý từ khóa.** Gợi ý tìm kiếm, từ khóa tinh chỉnh và những từ mà các pin hàng đầu dùng.

### <img src="https://cdn.simpleicons.org/twitch/9146FF" width="20" height="20" align="center" alt="Twitch" /> Twitch (2)

- **Gói emote.** Mọi emote và huy hiệu của một kênh, từ Twitch, BTTV, FFZ và 7TV, sắp xếp theo nhà cung cấp.
- **Trò chuyện VOD.** Toàn bộ bản phát lại trò chuyện của một VOD hoặc clip dưới dạng JSON, CSV và phụ đề, với các phút sôi động nhất được đánh dấu.

### <img src="https://cdn.simpleicons.org/bilibili/00A1D6" width="20" height="20" align="center" alt="Bilibili" /> Bilibili (2)

Việc tải video từ Bilibili nằm trên màn hình chính. Hai công cụ này liên quan đến bình luận nổi.

- **Xuất danmaku.** Danmaku của một video dưới dạng XML, ASS hoặc JSON mà không cần tải video.
- **Đốt danmaku.** Vẽ track bình luận lên một clip cục bộ và nhận một tập tin MP4 có thể chia sẻ.

### <img src="https://cdn.simpleicons.org/spotify/1DB954" width="20" height="20" align="center" alt="Spotify" /> Spotify (2)

- **Giao diện và màu sắc.** Tùy chỉnh trình khách Spotify bằng giao diện Spicetify. *beta*
- **Tiện ích mở rộng.** Cài đặt tiện ích mở rộng và ứng dụng tùy chỉnh của Spicetify từ Marketplace của nó. *beta*

### <img src="https://api.iconify.design/ph/music-notes.svg?color=%23FF5E7A" width="20" height="20" align="center" alt="Music" /> Âm nhạc (3)

- **Danh sách phát thành M3U.** Ghép một danh sách phát đã xuất với các tập tin âm thanh bạn sở hữu rồi ghi `.m3u8` và `.pls` cho bất kỳ trình phát cục bộ nào.
- **Lời bài hát đồng bộ.** Lấy lời từ LRCLIB và lưu một tập tin `.lrc` cạnh mỗi bài hát.
- **Lịch sử Spotify.** Mở bản xuất dữ liệu đầy đủ của bạn và xem mọi thứ mà Wrapped bỏ sót.

### <img src="https://api.iconify.design/simple-icons:linkedin.svg?color=%230A66C2" width="20" height="20" align="center" alt="LinkedIn" /> LinkedIn (4)

Cả bốn công cụ đều đọc bản xuất dữ liệu chính thức mà LinkedIn cho phép bạn yêu cầu, trên máy của bạn. Không có gì đăng nhập.

- **Tổng quan dữ liệu.** Kết nối, tin nhắn, bài đăng và những gì nhà quảng cáo biết về bạn.
- **Kết nối.** Lọc, nhóm và xuất danh sách kết nối của bạn.
- **Tin nhắn.** Duyệt lịch sử trò chuyện của bạn và lưu thành một trang cục bộ.
- **Điểm hồ sơ.** Kiểm tra mức độ hoàn chỉnh ngoại tuyến kèm những gì còn thiếu.

### <img src="https://api.iconify.design/ph/game-controller.svg?color=%233D5BF0" width="20" height="20" align="center" alt="Games" /> Trò chơi (3)

- **Album Switch.** Nhập ảnh chụp màn hình và clip từ thẻ SD của Switch, đặt tên theo trò chơi và ngày.
- **Sắp xếp clip.** Phân loại các bản ghi của Game Bar, ShadowPlay, OBS và Steam vào thư mục theo trò chơi.
- **Chạy được trên Linux?** Bậc ProtonDB cho một trò chơi hoặc toàn bộ thư viện Steam của bạn.

### <img src="https://api.iconify.design/ph/file-pdf.svg?color=%23E0303A" width="20" height="20" align="center" alt="PDF" /> PDF (13)

- **Gộp.** Nối nhiều tập tin PDF thành một, theo thứ tự bạn chọn.
- **Tách.** Trích xuất trang hoặc chia một tập tin PDF thành nhiều phần.
- **Nén.** Thu nhỏ một tập tin PDF mà vẫn đọc được.
- **Chuyển đổi.** PDF thành ảnh hoặc Word, và ngược lại.
- **OCR.** Làm cho các tập tin PDF quét được tìm kiếm được. *beta*
- **Sửa chữa.** Xây dựng lại một tập tin không mở được: bảng tham chiếu chéo hỏng, lượt tải bị cắt ngắn, rác trước tiêu đề.
- **Mật khẩu và quyền.** Khóa một tập tin PDF bằng AES-128, hoặc gỡ mật khẩu khỏi một tập tin bạn đã mở được.
- **Watermark và đánh số.** Đóng dấu văn bản lên mọi trang, hoặc đánh số Bates cho một loạt tập tin để lưu hồ sơ.
- **Cắt lề.** Cắt viền trắng để văn bản lấp đầy màn hình thiết bị đọc sách, tự phát hiện hoặc đặt bằng tay.
- **Mục lục.** Đọc các dấu trang mà một tập tin PDF có, hoặc tạo một dàn ý đúng cho tập tin chưa có.
- **Kiểm tra che mờ.** Tìm văn bản vẫn còn trong tập tin bên dưới một vạch đen, và đọc lại cho bạn.
- **PDF an toàn.** Xây dựng lại một tập tin PDF từ điểm ảnh để loại bỏ script và biểu mẫu.
- **PDF thành Markdown.** Markdown sạch với tiêu đề, danh sách và bảng, sẵn sàng dán vào một LLM.

### <img src="https://api.iconify.design/ph/file-text.svg?color=%231E6FE8" width="20" height="20" align="center" alt="Documents" /> Tài liệu (5)

- **SlideShare thành PDF.** Mọi slide ở kích thước lớn nhất, ghép thành một tập tin PDF.
- **Xuất Google Docs.** Docs, Slides và Sheets công khai thành PDF, DOCX, PPTX hoặc XLSX.
- **Trang Calameo.** Lưu các trang của một ấn phẩm Calameo dưới dạng SVG hoặc JPG. *beta*
- **Thư viện ảnh.** Toàn bộ thư viện và hồ sơ từ hơn 250 trang web với gallery-dl.
- **Scribd.** Lưu sách đọc được thành PDF bằng phiên của bạn. *planned*

### <img src="https://api.iconify.design/ph/images.svg?color=%23E0A800" width="20" height="20" align="center" alt="Images" /> Hình ảnh (9)

- **Nâng cấp.** Real-ESRGAN trên bất kỳ GPU Vulkan nào, 2x, 3x hoặc 4x. *beta*
- **Đổi kích thước ảnh.** Đổi kích thước hàng loạt theo chiều rộng, chiều cao, vừa khung hoặc phần trăm, đồng thời chuyển định dạng nếu bạn muốn.
- **Nén tới một dung lượng.** Đạt một mục tiêu tính bằng KB bằng cách tìm chất lượng tốt nhất mà vẫn vừa, và nói rõ khi không thể.
- **Siêu dữ liệu và GPS.** Xem một bức ảnh mang theo những gì, vị trí, máy ảnh và số sê-ri, rồi loại bỏ chúng mà không chạm vào điểm ảnh.
- **Ảnh trùng lặp.** Cùng một bức ảnh lưu hai lần, nén lại, đổi kích thước hoặc cắt xén, không chỉ các bản sao giống hệt từng byte.
- **Ghép ảnh chụp màn hình.** Nối các ảnh chụp màn hình cuộn thành một ảnh dài mà không lặp lại phần chồng nhau.
- **Gói biểu tượng.** Một hình ảnh thành `favicon.ico`, các PNG cho web, `apple-touch-icon` và một tập tin `.icns` cho macOS.
- **Spritesheet.** Cắt một bảng thành các khung, đóng gói các khung lại kèm atlas, hoặc đổi kích thước một thư mục theo quy tắc.
- **OCR.** Sao chép văn bản ra khỏi ảnh và slide. *beta*

### <img src="https://api.iconify.design/ph/broom.svg?color=%231A9EB5" width="20" height="20" align="center" alt="System" /> Hệ thống (10, các mục chỉ chạy trên Windows được đánh dấu)

- **Dọn bộ nhớ đệm.** Tập tin tạm, nhật ký và bộ nhớ đệm ứng dụng với quy tắc cho từng hệ điều hành. Bạn xem lại danh sách trước khi bất cứ thứ gì bị xóa.
- **Phân tích ổ đĩa.** Thứ gì chiếm dung lượng, dưới dạng treemap cộng các tập tin lớn nhất, với nút đưa vào thùng rác.
- **Chặn quảng cáo bằng hosts.** Trỏ các tên miền quảng cáo và đo lường về hư không, trong một khối riêng không bao giờ chạm vào các dòng của bạn.
- **Quản lý khởi động.** Xem thứ gì khởi chạy cùng hệ thống và tắt các mục. *beta*
- **Gỡ cài đặt.** Gỡ ứng dụng và các phần còn sót lại mà chúng để lại. *beta*
- **Lá chắn riêng tư.** Kiểm soát đo lường, ID quảng cáo và cài đặt theo dõi của Windows. Windows. *beta*
- **Tăng cường bảo mật Windows.** Macro, AutoRun, script host, UAC và cài đặt Defender theo hardentools, có thể hoàn tác. Windows. *beta*
- **Gỡ phần mềm rác Windows.** Gỡ các ứng dụng Store cài sẵn. Windows. *beta*
- **Dọn registry.** Các mục mồ côi, với bản sao lưu `.reg` trước khi xóa. Windows. *beta*
- **Cập nhật phần mềm.** Cập nhật nhiều chương trình cùng lúc qua winget, Chocolatey và Scoop. Windows. *beta*

### <img src="https://api.iconify.design/ph/folder-simple.svg?color=%23A66A24" width="20" height="20" align="center" alt="Files" /> Tập tin (5)

- **Trùng lặp.** Tìm các tập tin giống hệt theo hash và giải phóng dung lượng an toàn.
- **Đổi tên hàng loạt.** Regex, bộ đếm và đổi chữ hoa/thường với bản xem trước trước khi áp dụng.
- **Xóa an toàn.** Ghi đè tập tin trước khi xóa, để công cụ khôi phục không tìm được gì.
- **Tìm tập tin.** Tìm kiếm tức thì bằng Everything trên Windows, Spotlight trên macOS hoặc fd trên Linux.
- **Giữ máy thức.** Ngăn máy tính ngủ trong các công việc dài.

### <img src="https://api.iconify.design/ph/cloud-arrow-down.svg?color=%231E6FE8" width="20" height="20" align="center" alt="Downloads" /> Tải xuống (2)

- **Tải tăng tốc.** Tập tin lớn với 16 kết nối, tiếp tục tải và kiểm tra checksum qua aria2.
- **Danh sách phát HLS / DASH.** Dán một tập tin `.m3u8` hoặc `.mpd` kèm Referer và cookie. FFmpeg lưu thành MP4.

### <img src="https://api.iconify.design/ph/cursor-click.svg?color=%23F28500" width="20" height="20" align="center" alt="Automation" /> Tự động hóa (1)

- **Tự động nhấp chuột.** Nhấp với đúng tốc độ bạn đặt, kèm phím tắt toàn cục, giới hạn và khoảng ngẫu nhiên. Windows, macOS và Linux. *beta*

### <img src="https://api.iconify.design/ph/device-mobile.svg?color=%232AA845" width="20" height="20" align="center" alt="Phone" /> Điện thoại (1)

- **Gửi tới điện thoại.** Tập tin, liên kết và văn bản tới một thiết bị KDE Connect đã ghép nối.

### <img src="https://api.iconify.design/ph/sparkle.svg?color=%233D5BF0" width="20" height="20" align="center" alt="AI" /> AI (6)

- **So sánh giá.** Chi phí của cùng một mô hình trên các nhà cung cấp, với giá từ LiteLLM và models.dev.
- **Chi tiêu AI.** LibreGet đã chi bao nhiêu cho AI, theo ngày, mô hình và tác vụ, từ một sổ cái cục bộ.
- **Mô hình cục bộ (Ollama).** Xem, tải xuống và gỡ các mô hình cục bộ rồi dùng chúng làm nhà cung cấp miễn phí.
- **Viết lại cho giống người.** Viết lại văn bản nghe như AI để đọc như người viết, mà không đổi nội dung. Chạy trên nhà cung cấp AI bạn đã cấu hình. *beta*
- **Khóa API.** Một kho lưu trữ cục bộ cho khóa và tài khoản, kèm kiểm tra kết nối, số dư cho OpenRouter, DeepSeek, SiliconFlow và New API, và xuất sang Claude Code, Codex, Cherry Studio, opencode hoặc một tập tin `.env`.
- **Máy chủ MCP.** Các công cụ của LibreGet được phơi bày qua Model Context Protocol trên cầu nối cục bộ, 37 công cụ dùng chung token với tiện ích mở rộng, kèm đoạn cấu hình sẵn cho Claude Code, Claude Desktop, Cursor, VS Code, Goose và Codex. Xem [LibreGet cho AI agent](#libreget-cho-ai-agent-máy-chủ-mcp-và-plugin-claude-code). *beta*

### <img src="https://api.iconify.design/ph/sword.svg?color=%236F6F75" width="20" height="20" align="center" alt="CTF and analysis" /> CTF và phân tích (6)

Sáu tiện ích ngoại tuyến nhỏ cho các câu đố capture-the-flag, bài tập pháp y và những lúc "đây là tập tin gì".

- **Hash và HMAC.** MD5, họ SHA, CRC-32 và HMAC của văn bản hoặc tập tin, cộng với phỏng đoán về một hash chưa biết.
- **Đây là tập tin gì.** Chữ ký, chuỗi đọc được, entropy, và bất cứ thứ gì ẩn sau phần cuối của tập tin thật.
- **Mật mã cổ điển.** Caesar, ROT13, Atbash, Vigenère và Rail Fence, kèm thuật toán vét cạn chọn đáp án đọc được.
- **XOR.** Áp một khóa, hoặc khôi phục một khóa: một byte đơn theo tần suất chữ cái, một khóa lặp theo khoảng cách Hamming.
- **Mã hóa.** base64, base32, hex, URL, thực thể HTML, nhị phân và morse, cả hai chiều, kèm phát hiện.
- **Phân tích tần suất.** Biểu đồ, entropy và chỉ số trùng hợp, cùng ý nghĩa thường thấy của tổ hợp đó.

Mọi công cụ trò chuyện với AI đều dùng nhà cung cấp bạn đặt trong **Settings → AI**: OpenAI, Anthropic, hoặc bất kỳ điểm cuối tương thích OpenAI nào trên máy như Ollama hoặc LM Studio. Khóa được lưu cục bộ và không bao giờ ghi nhật ký. Trình tự động nhấp chuột, đọc chính tả và bộ đệm phát lại mỗi thứ có thể có một phím tắt toàn cục riêng.

---

## LibreGet cho AI agent: máy chủ MCP và plugin Claude Code

<p align="center">
  <img src="assets/readme/illustration-agents.png" alt="Linh vật chim cánh cụt ở terminal đưa một thư mục tập tin cho một robot nhỏ, robot đưa lại một liên kết, với các ô micro, phụ đề và video phía trên màn hình" width="900" />
</p>

Hai cánh cửa, tùy vào agent của bạn sống ở đâu.

**Trong ứng dụng: máy chủ MCP.** Bật lên trong Tools → AI → MCP server và LibreGet phơi bày 37 công cụ của nó qua Model Context Protocol trên cùng cầu nối cục bộ mà tiện ích trình duyệt dùng, đằng sau cùng một token cho mỗi bản cài. Một agent có thể xếp hàng một URL rồi theo dõi, tạm dừng, tiếp tục hoặc hủy nó trong bảng Downloads, gộp, tách, dựng, trích xuất văn bản từ hoặc làm sạch PDF, chuyển ngữ một tập tin bằng whisper.cpp, chạy chuyển văn bản thành giọng nói và OCR, đổi kích thước ảnh, tìm trùng lặp, tìm tập tin, đọc bài đăng, thread, hồ sơ, tìm kiếm và xu hướng trên X, tra cứu hồ sơ Instagram qua phiên của bạn, so sánh giá LLM, viết lại văn bản cho giống người, quét ổ đĩa và bộ nhớ đệm, liệt kê các mục khởi động và ứng dụng đã cài, và kéo các tập tin lớn hoặc thư viện bằng aria2 và gallery-dl. Trang in đoạn cấu hình cho Claude Code, Claude Desktop, Cursor, VS Code, Goose và Codex, nên đó là việc dán, không phải thiết lập. *beta*

**Trong Claude Code: plugin `libreget`.** Thư mục [`claude-plugin/`](claude-plugin/libreget) kèm một plugin cho [Claude Code](https://claude.com/claude-code) mà không cần ứng dụng máy tính. Dán một URL video, âm thanh hoặc bài đăng mạng xã hội kèm yêu cầu và các kỹ năng `libreget-fetch` và `libreget-transcribe` tự kích hoạt. Các lệnh gạch chéo có sẵn khi bạn muốn nói rõ:

```
/plugin marketplace add /path/to/libreget/claude-plugin
/plugin install libreget
/libreget:setup                       # installs yt-dlp, ffmpeg and libreget-cli after one confirmation
/libreget:fetch <url> [--audio]       # the media file, to ~/Downloads/libreget
/libreget:transcribe <url|file>       # captions, then local whisper.cpp, then Gemini or OpenAI if you added a key
/libreget:research <url>              # caption plus transcript distilled into a Markdown note with [mm:ss] references
/libreget:doctor                      # what is installed, what is missing, how to add it
```

Thiết lập tải `libreget-cli` đã biên dịch sẵn cho hệ điều hành của bạn, mang lại cho kỹ năng các trình trích xuất gốc Instagram, X, Bilibili và Threads của LibreGet. Một lượt tải thất bại vì tường đăng nhập sẽ được thử lại một lần với cookie của trình duyệt bạn đặt tên trong `LIBREGET_COOKIES_FROM_BROWSER`. Khóa API đi vào `~/.config/ai-keys.env` từ chính terminal của bạn và không bao giờ được in trả lại.

---

## Plugin: Courses, Telegram, Convert

Các plugin lõi được nhúng trực tiếp vào tập tin nhị phân của ứng dụng, loại bỏ lỗi tải xuống lúc chạy và lỗi tương thích ABI. Trang Marketplace hiện các plugin đang hoạt động, mỗi plugin được phép làm gì (sự kiện, thông báo, cài đặt, thư mục tải xuống, proxy, công cụ được quản lý, hàng đợi tải xuống), và cho phép bạn cấu hình hoặc bật/tắt chúng.

<p align="center">
  <img src="assets/readme/marketplace.png" alt="Marketplace của LibreGet liệt kê các plugin Courses, Telegram và Convert kèm phiên bản, tác giả, quyền và công tắc bật" width="900" />
</p>

### <img src="https://api.iconify.design/ph/graduation-cap.svg?color=%23F28500" width="20" height="20" align="center" alt="Courses" /> Courses

Plugin Courses tích hợp sẵn hỗ trợ 38 nền tảng học tập, gồm **Hotmart**, **Udemy**, **Kiwify**, **Rocketseat**, **Coursera**, **Domestika**, **Skillshare**, **Alura** và **Ebac**. Đăng nhập qua webview trong ứng dụng, bằng cookie đã lưu từ tiện ích mở rộng, hoặc bằng thông tin tài khoản khi có sẵn. LibreGet liệt kê các khóa bạn đã mua, mở dàn ý khóa học để bạn chọn các mục muốn tải (các bài giảng được bảo vệ DRM sẽ bị bỏ qua và báo cáo), rồi tải bài học và tập tin đính kèm kèm đánh số liên tục tùy chọn.

### <img src="https://cdn.simpleicons.org/telegram/2CA5E0" width="20" height="20" align="center" alt="Telegram" /> Telegram

Đăng nhập bằng mã QR hoặc số điện thoại của bạn. Duyệt mọi kênh và nhóm bạn tham gia, lọc theo ảnh, video, tài liệu hoặc âm thanh, tìm tập tin, và tải từng phương tiện hoặc toàn bộ kho lưu trữ trò chuyện kèm danh sách tiến độ. Các lượt tải phương tiện được sắp xếp vào `{download_dir}/LibreGram/{channel_name}/` với tên thư mục đã được làm sạch.

### <img src="https://api.iconify.design/ph/arrows-clockwise.svg?color=%232AA845" width="20" height="20" align="center" alt="Convert" /> Convert

Chuyển đổi FFmpeg với tăng tốc GPU khi máy có: định dạng chứa, codec, độ phân giải, bitrate và nén cho video và âm thanh, không cần internet.

---

## Mọi thứ khác trong hộp công cụ

- Bảng lệnh (**Ctrl+K** hoặc **Cmd+K**) nhảy tới bất kỳ trang, cài đặt hay công cụ nào.
- Phát hiện clipboard, đề nghị tải một liên kết đã sao chép chỉ bằng một cú nhấp trên thông báo.
- Trình quản lý cookie giữ phiên theo từng trang web, do tiện ích mở rộng ghi lại hoặc nhập từ một tập tin `cookies.txt`, với nút kiểm tra cho từng tên miền.
- Tóm tắt video: dán một URL trong **Settings → AI**, LibreGet lấy phụ đề và tóm tắt chúng với độ dài và ngôn ngữ bạn chọn.
- Gửi một tập tin cho ai đó: chọn một tập tin, chia sẻ mã từ, người kia dán mã vào LibreGet của họ.
- Discord Rich Presence hiện những gì bạn đang nghe, xem hoặc đọc. Các lượt tải vẫn riêng tư.
- Biểu tượng khay hệ thống, khởi động cùng hệ thống, khởi động thu nhỏ, ngăn máy ngủ trong lúc tải xuống.
- Mọi lượt tải đều giữ chính xác lệnh yt-dlp mà nó đã chạy. Mở ra, sửa một cờ, thử lại.
- 14 giao diện, gồm Catppuccin (bốn biến thể), Dracula, One Dark Pro, ba biến thể e-ink và ba biến thể Nyxvamp.
- 12 ngôn ngữ: tiếng Anh, tiếng Bồ Đào Nha, tiếng Tây Ban Nha, tiếng Pháp, tiếng Ý, tiếng Hy Lạp, tiếng Nga, tiếng Nhật, tiếng Ba Tư, tiếng Lào, tiếng Trung giản thể và phồn thể.
- Chạy trên Windows, macOS (Apple Silicon và Intel) và Linux (x86_64 và ARM64).

---

## Quyền riêng tư và những gì LibreGet từ chối làm

<p align="center">
  <img src="assets/readme/illustration-privacy.png" alt="Linh vật chim cánh cụt ôm một chiếc laptop với biểu tượng tải xuống của LibreGet và một ổ khóa xanh, bên trong một chiếc khiên phát sáng" width="700" />
</p>

Mọi thứ chạy trên máy tính của bạn. Không có tài khoản, không có máy chủ nào của chúng tôi ở giữa, và không có dữ liệu đo lường nào về những gì bạn tải xuống. Cookie và khóa API nằm trong hồ sơ cục bộ của bạn. Những cuộc gọi mạng duy nhất mà LibreGet tự thực hiện là tới các trang web bạn yêu cầu tải xuống, tới GitHub để cập nhật và plugin, và tới nhà cung cấp AI bạn đã cấu hình, khi bạn dùng một công cụ AI.

LibreGet tải xuống những gì phiên đăng nhập của chính bạn đã mở được. Nó không vượt qua DRM, không phá tường trả phí, không chia sẻ thông tin đăng nhập, và các bài giảng được bảo vệ DRM sẽ bị bỏ qua và báo cáo. Bạn có trách nhiệm tôn trọng bản quyền và điều khoản dịch vụ của từng nền tảng. Toàn văn nằm trong ứng dụng ở mục **About → Terms and ethics**.

---

## Chính sách ký mã

Dịch vụ ký mã miễn phí trên Windows do [SignPath.io](https://about.signpath.io) cung cấp, chứng chỉ của [SignPath Foundation](https://signpath.org).

Các thay đổi mã và bản phát hành đã ký được các maintainer TongQuocTuan xem xét và phê duyệt. Xem [Quyền riêng tư và những gì LibreGet từ chối làm](#quyền-riêng-tư-và-những-gì-libreget-từ-chối-làm) để biết cách LibreGet xử lý dữ liệu.

---

## Câu hỏi thường gặp

**LibreGet có miễn phí không?**
Có. GPL-3.0, không có gói trả phí, không quảng cáo, không tài khoản.

**LibreGet có phải là giao diện đồ họa của yt-dlp không?**
Một phần. yt-dlp xử lý phần dài các trang web và LibreGet đóng gói, xác minh và cập nhật nó. Trên đó còn có các trình trích xuất gốc cho khóa học, Instagram, X, Pinterest, Bilibili, Telegram và torrent, một hàng đợi có tiếp tục tải và thử lại, mục Tools, và chuyển đổi đa phương tiện.

**LibreGet có tải được khóa học Udemy hoặc Hotmart mà tôi đã mua không?**
Có. Plugin Courses được nhúng trực tiếp trong ứng dụng. Đăng nhập qua ứng dụng, chọn khóa học và các mục, rồi tải xuống. Bài học và tập tin đính kèm nằm trong một thư mục có tổ chức cho từng khóa học. 38 nền tảng được hỗ trợ, gồm Hotmart, Udemy, Kiwify, Rocketseat, Coursera, Domestika và nhiều nền tảng khác.

**Nó có tải được Instagram stories, bạn thân hoặc highlights không?**
Có, dùng phiên của bạn do tiện ích trình duyệt ghi lại. Stories được tải mà không bị đánh dấu là đã xem.

**Nó có tải được một video X, toàn bộ thread hoặc mọi media từ một hồ sơ không?**
Có. Bài đăng công khai không cần đăng nhập. Bookmark và danh sách theo dõi của bạn cần phiên X của bạn.

**Nó có sao lưu được một bảng Pinterest với chất lượng gốc không?**
Có, gồm video, mục, bảng bí mật với cookie, và đồng bộ tăng dần để bạn chỉ lấy những gì mới.

**Nó có tiếp tục các lượt tải bị ngắt không?**
Có. Các tập tin tải dở được giữ lại và tiếp tục, và giới hạn tốc độ kích hoạt thử lại với thời gian chờ tăng dần.

**Nó lưu được những định dạng nào?**
Video dưới dạng MP4, MKV hoặc WebM. Âm thanh dưới dạng MP3, M4A, Opus, FLAC hoặc WAV. Phụ đề dưới dạng SRT, VTT hoặc ASS, nhúng hoặc đặt cạnh tập tin.

**Nó có cần Python, Node hay terminal không?**
Không. Tải ứng dụng, mở ra, dán một liên kết. Bước terminal duy nhất là cách sửa Gatekeeper trên macOS một lần ở trên.

**macOS báo ứng dụng bị hỏng.**
Chạy hai lệnh trong [mục cảnh báo lần khởi chạy đầu tiên](#cảnh-báo-ở-lần-khởi-chạy-đầu-tiên-và-cách-xử-lý). Chuyện này xảy ra vì ứng dụng chưa được notarize, và chỉ xảy ra một lần.

**Nó có đọc được bản xuất dữ liệu Reddit, LinkedIn, Spotify, X hoặc Instagram của tôi không?**
Có. Yêu cầu bản xuất từ nền tảng, rồi mở tập tin zip trong công cụ tương ứng. Nó được phân tích trên máy của bạn và không có gì được tải lên.

**AI agent có dùng được LibreGet không?**
Có, hai cách. Máy chủ MCP trong Tools → AI phơi bày 37 công cụ cho Claude Code, Claude Desktop, Cursor, VS Code, Goose và Codex, và thư mục `claude-plugin/` kèm một plugin Claude Code lấy và chuyển ngữ media mà không cần ứng dụng máy tính. Xem [LibreGet cho AI agent](#libreget-cho-ai-agent-máy-chủ-mcp-và-plugin-claude-code).

**Tôi có chuyển ngữ một video thành phụ đề ngoại tuyến được không?**
Có. Tools → Speech and subtitles → Transcribe dùng whisper.cpp cục bộ. Các mô hình tải theo nhu cầu.

**Tôi có chạy nó từ USB được không?**
Có, trên Windows, với một tập tin `portable.txt` cạnh tập tin thực thi.

**Tôi nên chọn gói Linux nào?**
Debian và Ubuntu: `.deb`. Fedora, openSUSE, họ RHEL: `.rpm`. Mọi trường hợp khác: `.AppImage`. Cả x86_64 và ARM64 đều được phát hành. LibreGet không có trên Flathub.

---

## Dòng lệnh

`libreget-cli` đi kèm mọi bản phát hành cho Windows, macOS (Intel và Apple Silicon) và Linux. Lấy `libreget-cli-<version>-<target>` từ [bản phát hành mới nhất](https://github.com/TongQuocTuan/libreget/releases/latest).

```bash
libreget info <url>                     # title, formats and size, downloads nothing
libreget download <url> -q 1080 -o ~/Videos
libreget download <url> --audio-only --subs en,pt
libreget batch links.txt -m 3           # one URL per line, 3 at a time
libreget import-cookies cookies.txt     # Netscape format
```

---

## Biên dịch từ mã nguồn

Nếu bạn chỉ muốn dùng LibreGet, [hãy lấy một bản phát hành](#tải-xuống-và-cài-đặt). Để biên dịch, bạn cần [Rust](https://rustup.rs/) (toolchain chính xác được ghim trong `rust-toolchain.toml` vì ABI của plugin phụ thuộc vào nó), [Node.js](https://nodejs.org/) 18+ và [pnpm](https://pnpm.io/).

```bash
git clone https://github.com/TongQuocTuan/libreget.git
cd libreget
pnpm install
pnpm tauri dev
```

<details>
<summary>Linux build dependencies</summary>

```bash
sudo apt-get install -y libwebkit2gtk-4.1-dev build-essential curl wget file libxdo-dev libssl-dev \
  libayatana-appindicator3-dev librsvg2-dev patchelf libasound2-dev libpipewire-0.3-dev clang libclang-dev
```

</details>

Bản dựng production:

```bash
pnpm tauri build --config '{"bundle":{"createUpdaterArtifacts":false}}'
```

Các bản phát hành ký artifact cập nhật bằng một khóa riêng tư mà chỉ maintainer giữ, nên một lệnh `pnpm tauri build` thông thường sẽ dừng với thông báo "A public key has been found, but no private key". Cờ trên tắt các artifact đó cho bản dựng cục bộ và không đổi gì khác.

Các plugin `courses`, `telegram` và `convert` nằm trong `src-tauri/plugins/` và biên dịch vào tập tin nhị phân chính. Registry plugin là [libreget-plugins](https://github.com/TongQuocTuan/libreget-plugins).

Stack: Tauri 2, Rust, SvelteKit với Svelte 5, SQLite, yt-dlp, FFmpeg, librqbit cho torrent, whisper.cpp, aria2, gallery-dl.

---

## Đóng góp và bản dịch


Bản dịch được quản lý trên [Weblate](https://hosted.weblate.org/engage/libreget/). Chọn ngôn ngữ của bạn rồi dịch trong trình duyệt. Các chuỗi mới xuất hiện ở đó vài giờ sau khi chúng vào `main`.

LibreGet được xây dựng trên [yt-dlp](https://github.com/yt-dlp/yt-dlp), [FFmpeg](https://ffmpeg.org/), [gallery-dl](https://github.com/mikf/gallery-dl), [whisper.cpp](https://github.com/ggerganov/whisper.cpp), [aria2](https://aria2.github.io/), [SponsorBlock](https://sponsor.ajay.app/), [Return YouTube Dislike](https://returnyoutubedislike.com/), [FxTwitter](https://github.com/FixTweet/FxTwitter), [Spicetify](https://spicetify.app/), [cat-catch](https://github.com/xifangczy/cat-catch) (các phần của trình dò tìm media trong tiện ích mở rộng) và [Tauri](https://tauri.app/). Cảm ơn mọi người đã duy trì chúng.

Linh vật chim cánh cụt là linh vật của dự án LibreGet. Fan art của cộng đồng luôn được chào đón. Tài sản thương hiệu của dự án không được dùng cho mục đích thương mại hay đóng gói vào các fork gây hiểu lầm của bên thứ ba khi chưa được phép.

<p align="center">
  <a href="https://star-history.com/#TongQuocTuan/libreget&Date"><img src="https://api.star-history.com/svg?repos=TongQuocTuan/libreget&type=Date" alt="Star history of TongQuocTuan/libreget" width="600" /></a>
</p>

<p align="center">
  <a href="https://github.com/TongQuocTuan/libreget/releases/latest"><b>Tải xuống LibreGet</b></a> · <a href="LICENSE">GPL-3.0</a>
</p>
