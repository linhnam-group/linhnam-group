# Nhật ký phát hành · Changelog

Những thay đổi đã đưa vào hoạt động trên các hệ thống của Lĩnh Nam Group, mới nhất ở trên. Chỉ ghi tính năng và kết quả; chi tiết kỹ thuật nội bộ không công bố.

<sub>Tiếng Việt · [English](#english) · [中文](#中文) · [Русский](#русский) · [한국어](#한국어)</sub>

### 14/11/2026
- **ERP — Tin tức:** bố cục mới cho biên tập viên: bảng bài viết ở đầu trang, lọc theo trạng thái bằng thanh có số đếm, một ô tìm kiếm duy nhất, và cột cho biết bài đã có đủ 5 ngôn ngữ trên website của đơn vị hay chưa.
- **ERP — Tin tức:** danh sách bài tải nhẹ hơn khoảng 17 lần (từ khoảng 2,2 MB xuống khoảng 130 KB); trang Quy trình nội dung cũng dùng danh sách gọn này.
- **Website — Tin liên quan:** không còn gợi ý bài đã gỡ hoặc bài không có trang trên website đó.
- **Mã nguồn:** kho mã API chạy kiểm thử tự động và quét bí mật trên GitHub mỗi lần cập nhật.

### 13/11/2026
- **ERP — Tin tức:** một bài viết gắn được nhiều chuyên mục.
- **ERP — Trình soạn tin:** gỡ tính năng dịch tự động; bỏ hộp thoại thừa khi đăng bài; nội dung đổi đúng theo từng tab ngôn ngữ.
- **linhnam.store:** bài chưa có bản dịch chỉ đăng ở trang tiếng Việt, trang ngôn ngữ khác không còn hiện chữ Việt.

### 11/11/2026
- **ERP và cdrestop.com:** nâng lên Next.js 16.
- **API:** siết phân quyền đọc — dữ liệu sở hữu, nhân sự và tài chính chỉ trả cho vai trò được phép.
- **API:** vá lỗ hổng ở cách các API công khai xử lý tham số ngôn ngữ.
- **ERP — Cổng nhân sự:** trang chủ gọn lại, danh bạ lọc theo đơn vị.
- **ERP — Tổ chức:** sửa hiển thị cây tổ chức và bộ lọc trạng thái.
- **cdrestop.com:** trang Nhà tài trợ có ảnh xem trước khi chia sẻ; mọi địa chỉ thư in trên trang đều nhận được thư.
- **Bảo mật:** quét bí mật trong CI của ERP, cập nhật các thư viện có lỗ hổng, bật cảnh báo phụ thuộc cho các kho mã chính.

### 10/11/2026
- **Trang trạng thái** [linhnam-group.github.io/status](https://linhnam-group.github.io/status/): đo 7 website mỗi 5 phút, công khai kết quả.
- **Hồ sơ GitHub:** mục Đồng hành và tài trợ; chính sách bảo mật và hướng dẫn đóng góp dùng chung cho các kho mã.

### 07/11/2026
- **ERP:** hộp duyệt chung và khu «Chờ duyệt — tin».
- **ERP — Cổng nhân sự:** sửa đăng nhập và làm mới phiên.
- **ERP:** đăng bài hẹn giờ.

---

<a id="english"></a>

## English

Changes put into production across Lĩnh Nam Group systems, newest first. Features and outcomes only; internal technical details are not published.

### 14 Nov 2026
- **ERP — News:** new editor-desk layout: the article table comes first, status filter tabs with counts, a single search box, and a column showing whether each article is available in all five languages on its business unit's website.
- **ERP — News:** the article list is about 17 times lighter to load (from about 2.2 MB to about 130 KB); the content workflow page uses the same lightweight list.
- **Websites — related articles:** no longer suggest removed articles or articles without a page on that site.
- **Source code:** the API repository runs its automated tests and a secret scan on GitHub on every update.

### 13 Nov 2026
- **ERP — News:** an article can belong to several categories.
- **ERP — Article editor:** automatic translation removed; no redundant dialog when publishing; content switches correctly between language tabs.
- **linhnam.store:** articles without a translation are published on the Vietnamese pages only, so other-language pages no longer show Vietnamese text.

### 11 Nov 2026
- **ERP and cdrestop.com:** upgraded to Next.js 16.
- **API:** tighter read permissions: ownership, HR and finance data is returned only to authorised roles.
- **API:** fixed a vulnerability in how public endpoints handle the language parameter.
- **ERP — Staff portal:** simpler home screen; staff directory filterable by business unit.
- **ERP — Organisations:** fixed the organisation tree display and status filters.
- **cdrestop.com:** the Sponsors page has a share preview image; every email address listed on the site receives mail.
- **Security:** secret scanning in the ERP CI, vulnerable libraries updated, dependency alerts enabled on the main repositories.

### 10 Nov 2026
- **Status page** [linhnam-group.github.io/status](https://linhnam-group.github.io/status/): 7 websites checked every 5 minutes, results published openly.
- **GitHub profile:** sponsorship and partnership section; a shared security policy and contribution guide for all repositories.

### 7 Nov 2026
- **ERP:** shared approval inbox and a "Pending review — news" area.
- **ERP — Staff portal:** fixed sign-in and session refresh.
- **ERP:** scheduled publishing of articles.

---

<a id="中文"></a>

## 中文

岭南集团各系统已上线的更新，最新的在前。仅记录功能与成果，不公开内部技术细节。

### 2026年11月14日
- **ERP — 新闻：** 面向编辑的新布局：文章列表置于页首，带数量的状态筛选标签，统一的搜索框，并新增一列显示每篇文章在所属单位网站上是否已具备全部五种语言。
- **ERP — 新闻：** 文章列表的加载量减少约17倍（由约2.2 MB降至约130 KB）；内容流程页面也改用同一精简列表。
- **网站 — 相关文章：** 不再推荐已删除的文章或在该网站上没有页面的文章。
- **源代码：** API 代码库每次更新都会在 GitHub 上运行自动化测试和密钥扫描。

### 2026年11月13日
- **ERP — 新闻：** 一篇文章可归入多个栏目。
- **ERP — 文章编辑器：** 移除自动翻译；发布时不再弹出多余的对话框；切换语言标签时内容正确切换。
- **linhnam.store：** 尚无译文的文章只在越南语页面发布，其他语言页面不再显示越南语文字。

### 2026年11月11日
- **ERP 与 cdrestop.com：** 升级至 Next.js 16。
- **API：** 收紧读取权限：所有权、人事和财务数据仅向获授权的角色返回。
- **API：** 修复公开接口处理语言参数时的安全漏洞。
- **ERP — 员工门户：** 首页更简洁，员工通讯录可按单位筛选。
- **ERP — 组织：** 修复组织树显示和状态筛选。
- **cdrestop.com：** 赞助商页面分享时显示预览图；网站上列出的所有电子邮件地址均可正常收信。
- **安全：** ERP 持续集成中加入密钥扫描，更新存在漏洞的依赖库，并为主要代码库启用依赖警报。

### 2026年11月10日
- **状态页** [linhnam-group.github.io/status](https://linhnam-group.github.io/status/)：每5分钟检测7个网站，并公开结果。
- **GitHub 主页：** 新增赞助与合作栏目；为所有代码库提供统一的安全政策和贡献指南。

### 2026年11月7日
- **ERP：** 统一审批收件箱和“待审核 — 新闻”区域。
- **ERP — 员工门户：** 修复登录和会话刷新。
- **ERP：** 文章定时发布。

---

<a id="русский"></a>

## Русский

Изменения, введённые в работу в системах Lĩnh Nam Group, новые сверху. Только функции и результаты; внутренние технические подробности не публикуются.

### 14.11.2026
- **ERP — Новости:** новая раскладка для редакторов: таблица статей в начале страницы, вкладки-фильтры по статусу со счётчиками, единое поле поиска и столбец, показывающий, доступна ли статья на всех пяти языках на сайте своей компании.
- **ERP — Новости:** список статей загружается примерно в 17 раз легче (около 2,2 МБ → около 130 КБ); страница процесса публикации использует тот же облегчённый список.
- **Сайты — похожие статьи:** больше не предлагают удалённые статьи и статьи, у которых нет страницы на этом сайте.
- **Исходный код:** при каждом обновлении репозитория API на GitHub запускаются автотесты и проверка на утечку секретов.

### 13.11.2026
- **ERP — Новости:** статью можно отнести к нескольким рубрикам.
- **ERP — Редактор статей:** удалён автоматический перевод; при публикации больше нет лишнего диалога; содержимое правильно переключается между вкладками языков.
- **linhnam.store:** статьи без перевода публикуются только на вьетнамских страницах, поэтому страницы на других языках больше не показывают вьетнамский текст.

### 11.11.2026
- **ERP и cdrestop.com:** обновлены до Next.js 16.
- **API:** ужесточены права на чтение: данные о собственности, персонале и финансах выдаются только уполномоченным ролям.
- **API:** исправлена уязвимость в обработке языкового параметра публичными методами.
- **ERP — портал сотрудников:** упрощена главная страница; справочник сотрудников с фильтром по компании.
- **ERP — Организации:** исправлены отображение дерева организаций и фильтры по статусу.
- **cdrestop.com:** у страницы для спонсоров появилось изображение для предпросмотра ссылки; все адреса электронной почты, указанные на сайте, принимают письма.
- **Безопасность:** проверка на секреты в CI ERP, обновлены библиотеки с уязвимостями, включены оповещения о зависимостях в основных репозиториях.

### 10.11.2026
- **Страница статуса** [linhnam-group.github.io/status](https://linhnam-group.github.io/status/): 7 сайтов проверяются каждые 5 минут, результаты открыты.
- **Профиль GitHub:** раздел о спонсорстве и партнёрстве; общая политика безопасности и руководство для участников для всех репозиториев.

### 07.11.2026
- **ERP:** общий ящик согласований и раздел «На проверке — новости».
- **ERP — портал сотрудников:** исправлены вход и обновление сеанса.
- **ERP:** публикация статей по расписанию.

---

<a id="한국어"></a>

## 한국어

Lĩnh Nam Group 시스템에 실제 적용된 변경 사항이며, 최신 항목이 위에 있습니다. 기능과 결과만 기록하며 내부 기술 세부 사항은 공개하지 않습니다.

### 2026년 11월 14일
- **ERP — 뉴스:** 편집자를 위한 새 레이아웃: 기사 표를 맨 위에 두고, 개수가 표시되는 상태 필터 탭, 하나로 통합된 검색창, 그리고 각 기사가 소속 법인 웹사이트에서 5개 언어를 모두 갖췄는지 보여 주는 열을 추가했습니다.
- **ERP — 뉴스:** 기사 목록 로딩 용량이 약 17분의 1로 줄었습니다(약 2.2MB → 약 130KB). 콘텐츠 워크플로 페이지도 같은 경량 목록을 사용합니다.
- **웹사이트 — 관련 기사:** 삭제된 기사나 해당 사이트에 페이지가 없는 기사를 더 이상 추천하지 않습니다.
- **소스 코드:** API 저장소가 업데이트될 때마다 GitHub에서 자동 테스트와 비밀 정보 스캔을 실행합니다.

### 2026년 11월 13일
- **ERP — 뉴스:** 기사 하나를 여러 카테고리에 지정할 수 있습니다.
- **ERP — 기사 편집기:** 자동 번역 기능을 제거했습니다. 게시할 때 불필요한 대화 상자가 나타나지 않으며, 언어 탭을 바꾸면 내용이 올바르게 전환됩니다.
- **linhnam.store:** 번역이 없는 기사는 베트남어 페이지에만 게시되어, 다른 언어 페이지에 베트남어 텍스트가 더 이상 표시되지 않습니다.

### 2026년 11월 11일
- **ERP 및 cdrestop.com:** Next.js 16으로 업그레이드했습니다.
- **API:** 읽기 권한을 강화하여 소유 구조·인사·재무 데이터는 권한이 있는 역할에만 제공합니다.
- **API:** 공개 API가 언어 매개변수를 처리하는 방식의 보안 취약점을 수정했습니다.
- **ERP — 직원 포털:** 홈 화면을 간소화하고 직원 명부를 법인별로 필터링할 수 있습니다.
- **ERP — 조직:** 조직도 표시와 상태 필터를 수정했습니다.
- **cdrestop.com:** 후원사 페이지를 공유할 때 미리보기 이미지가 표시되며, 사이트에 게시된 모든 이메일 주소가 메일을 수신합니다.
- **보안:** ERP CI에 비밀 정보 스캔을 추가하고, 취약한 라이브러리를 업데이트했으며, 주요 저장소에서 의존성 경고를 활성화했습니다.

### 2026년 11월 10일
- **상태 페이지** [linhnam-group.github.io/status](https://linhnam-group.github.io/status/): 7개 웹사이트를 5분마다 점검하고 결과를 공개합니다.
- **GitHub 프로필:** 후원 및 협력 섹션을 추가하고, 모든 저장소에 공통 보안 정책과 기여 안내를 제공합니다.

### 2026년 11월 7일
- **ERP:** 통합 승인함과 '검토 대기 — 뉴스' 영역.
- **ERP — 직원 포털:** 로그인과 세션 갱신을 수정했습니다.
- **ERP:** 기사 예약 게시.
