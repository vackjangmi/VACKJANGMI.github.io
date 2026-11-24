---
layout: doc
title: 쓸만한 탭그룹 브라우저 개인정보처리방침
app_title: 쓸만한 탭그룹 브라우저
app_url: /apps/tabgroup-browswer/
---

## 🇰🇷 개인정보처리방침

쓸만한 탭그룹 브라우저(이하 "앱")는 일반적인 회원정보 수집형 서비스가 아니라, 브라우징 및 탭 그룹 데이터를 **주로 이용자 기기 내부에 저장**하여 세션 복원, 탭 그룹 관리, 백업/복원 기능을 제공하는 앱입니다.

본 문서는 앱이 어떤 정보를 기기 내부에 저장할 수 있는지, 그 목적이 무엇인지, 그리고 외부 웹사이트 및 외부 앱 링크 처리 시 어떤 점을 알아두셔야 하는지를 설명합니다.

앱은 **Google AdMob 광고와 Google Analytics for Firebase 이용 통계**를 사용합니다. 아래 내용은 Android 및 iOS 앱 1.0.12부터 추가되는 이용 통계를 포함합니다. 최종 수정일: 2026년 11월 24일.

---

### 1. 앱이 저장·처리하는 정보

앱은 다음 정보를 **주로 이용자 기기 내부에 저장**할 수 있습니다.

- 탭 그룹 및 세션 정보
- 열려 있는 탭 목록과 각 탭의 상태
- 방문 URL 및 브라우징 기록
- 앱 설정값
- 세션 복원 및 탭 그룹 전환을 위한 쿠키 정보 또는 쿠키 스냅샷
- 자동 백업 파일 및 복원에 필요한 로컬 데이터
- 비공개 탭 그룹 설정값 및 탭 그룹 목록 숨김 상태

또한 이용자 동작에 따라 다음과 같은 파일이 생성될 수 있습니다.

- 암호화된 탭 그룹 백업 파일 (`.tbg`)
- 암호화된 전체 백업 파일 (`.tbbak`)

현재 확인된 범위에서는, 회원정보나 브라우징 데이터를 개발자 운영 서버로 보내는 앱의 핵심 기능은 확인되지 않았습니다. 다만 광고 SDK 등 제3자 구성요소는 각자의 정책에 따라 정보를 처리할 수 있습니다.

---

### 2. 정보의 이용 목적

앱은 기기 내부에 저장된 정보를 다음 목적을 위해 사용합니다.

- 탭 그룹 열기 및 전환
- 브라우징 세션 유지 및 복원
- 방문 기록 및 자동완성 제공
- 앱 설정 저장
- 탭 그룹 백업/복원 및 전체 백업/복원
- 탭 그룹 목록 표시, 순서 변경, 기본 탭 그룹 선택
- 비공개 탭 그룹 숨김 및 재진입 제어
- 외부 앱 링크 처리 및 관련 제어 기능 제공
- 쿠키, 웹 저장소, 캐시 등 브라우저 데이터 관리
- 배너 광고 로드 및 표시
- 앱 이용 통계 분석 및 기능 개선

---

### 3. 보관 위치 및 보관 방식

위 정보는 원칙적으로 **이용자 기기 내부 저장소**에 보관됩니다.

- 앱은 브라우징 관련 데이터를 주로 로컬 저장소에 보관합니다.
- 생성된 백업 파일은 이용자가 저장 또는 내보내기한 위치에 따라 기기 내부 또는 이용자가 선택한 저장 위치에 보관될 수 있습니다.
- 현재 확인된 범위에서는, 이러한 데이터를 개발자 운영 서버에 업로드해 저장하거나 열람하는 기본 기능은 확인되지 않았습니다.
- 비공개 탭 그룹 여부, 탭 그룹 순서, 기본 탭 그룹 같은 설정값도 기기 내부에 저장될 수 있습니다.

---

### 4. 백업 파일 및 암호화

앱은 탭 그룹 또는 전체 데이터를 백업/복원할 수 있는 기능을 제공할 수 있습니다.

- 이용자가 백업을 실행하면 암호화된 백업 파일이 생성될 수 있습니다.
- 이러한 파일은 이용자의 선택에 따라 저장, 이동, 내보내기될 수 있습니다.
- 백업 파일의 보관, 전달, 공유 책임은 이용자에게 있습니다.

앱은 백업 파일 보호를 위해 보안 기능을 적용할 수 있으나, 모든 저장 환경이나 외부 전송 과정에 대해 절대적인 안전을 보장하는 것은 아닙니다.

---

### 5. 외부 웹사이트 및 외부 앱 링크 처리

앱은 브라우저 앱의 특성상 이용자가 연 웹사이트와 통신할 수 있으며, 일부 링크는 외부 앱으로 열릴 수 있습니다.

- 이용자가 앱에서 특정 웹사이트를 열면, 해당 웹사이트는 자체 정책에 따라 쿠키, 로컬 저장소, 접속 정보 등을 처리할 수 있습니다.
- `mailto:`, `tel:`, Kakao 계열 링크 등 일부 링크는 외부 앱으로 전달되어 열릴 수 있습니다.
- 외부 웹사이트 또는 외부 앱에서의 정보 처리에는 **각 서비스의 개인정보처리방침 또는 정책이 적용**됩니다.

따라서 본 개인정보처리방침은 **이 앱 자체의 데이터 처리 방식**에 적용되며, 이용자가 방문한 제3자 웹사이트나 외부 앱의 행위까지 통제하거나 대신 설명하지 않습니다.

---

### 6. 광고, 이용 통계 및 제3자 SDK

**Google AdMob**은 배너 광고를 제공합니다. 광고 SDK는 광고 제공, 광고 성과 분석, 오류 진단 및 부정 사용 방지를 위해 IP 주소 및 그로부터 추정한 대략적인 위치, 기기·광고 식별자, 앱 및 광고와의 상호작용, 오류·성능 정보를 수집·공유할 수 있습니다. 광고 식별자의 이용 가능 여부는 운영체제의 권한과 이용자 설정에 따릅니다.

**Google Analytics for Firebase**는 앱 실행, 세션 및 이용 시간과 같은 자동 이용 통계와, 탭·탭 그룹을 새로 만드는 동작의 횟수를 수집하여 앱 이용 현황을 분석하고 기능을 개선하는 데 사용됩니다.

- 통계에는 앱 설치 인스턴스 식별자, 앱 버전, 기기 모델·운영체제·언어, IP 주소에서 추정한 대략적인 지역 등이 포함될 수 있으며 Google 서버로 전송됩니다.
- 앱은 이름, 이메일, 계정 ID를 Analytics에 설정하지 않습니다. 설치 식별자가 있으므로 통계를 완전히 익명인 데이터로 간주하지 않습니다.
- 방문 URL, 검색어, 페이지 제목, 방문 기록, 탭 그룹 이름·코드, 쿠키 및 백업 파일의 내용을 Analytics 이벤트로 보내지 않습니다.
- 비공개 탭 그룹에서 탭을 새로 만드는 동작은 별도 통계 이벤트에서 제외됩니다. 앱 실행·세션 등의 자동 통계는 비공개 그룹을 이용하는 동안에도 수집될 수 있습니다.
- Analytics의 광고 식별자 수집, iOS IDFV 수집 및 광고 개인화 신호는 비활성화합니다. 이는 AdMob 광고 SDK의 별도 정보 처리까지 비활성화한다는 의미는 아닙니다.
- Android 및 iOS 앱의 Firebase 이용 통계를 해당 앱의 AdMob 보고서에 연결하여 이용자·광고 성과를 함께 확인합니다.

통계는 앱 시작 후 자동으로 수집되며 현재 앱 내에 통계 수집을 끄는 별도 설정은 없습니다. 전송 중에는 암호화되며, Google이 보관하는 통계 및 광고 데이터에는 각 서비스의 보관·삭제 정책이 적용됩니다. 앱 삭제나 로컬 데이터 삭제만으로 이미 전송된 통계가 즉시 삭제되지는 않습니다.

- [Google 개인정보처리방침](https://policies.google.com/privacy)
- [Firebase 개인정보 보호 및 보안](https://firebase.google.com/support/privacy)
- [Google Analytics 데이터 수집](https://support.google.com/analytics/answer/11593727)

---

### 7. 제3자 제공

현재 확인된 범위에서는, 이용자의 브라우징 데이터, 세션 데이터, 탭 그룹 데이터 등을 개발자 운영 서버를 통해 제3자에게 제공하는 기본 구조는 확인되지 않았습니다.

다만 다음 경우에는 정보가 외부 서비스로 전달될 수 있습니다.

- 이용자가 직접 웹사이트에 접속하는 경우
- 이용자가 외부 앱 링크를 실행하는 경우
- 광고 SDK가 광고 표시를 위해 자체적으로 필요한 정보를 처리하는 경우
- Firebase Analytics가 앱 이용 통계를 수집하고 연결된 AdMob 보고서에서 사용하는 경우
- 이용자가 백업 파일을 외부 서비스 또는 외부 저장 위치로 직접 이동·공유하는 경우

이 경우 해당 정보 처리는 이용자가 선택한 웹사이트, 앱, 저장 서비스의 정책에 따릅니다.

---

### 8. 삭제 및 이용자 통제 방법

이용자는 앱 내 기능을 통해 저장된 데이터를 직접 관리하거나 삭제할 수 있습니다.

예를 들어 다음과 같은 기능이 제공될 수 있습니다.

- 현재 사이트 쿠키 및 웹 저장소 삭제
- 전체 쿠키 삭제
- 전체 캐시 삭제
- 전체 데이터 삭제
- 탭 그룹 삭제
- 비공개 탭 그룹 설정 해제
- 백업 파일 직접 삭제

백업 파일이 앱 외부 저장소에 저장된 경우에는, 해당 파일을 저장한 위치에서 이용자가 직접 삭제해야 할 수 있습니다.

비공개 탭 그룹은 탭 그룹 목록에서 숨겨질 수 있으나, 해당 탭 그룹 자체가 자동으로 삭제되는 것은 아닙니다.

광고 개인화 및 광고 식별자는 기기의 개인정보 보호·광고 설정에서 관리할 수 있습니다. 광고 설정 변경은 Analytics 이용 통계 수집을 끄는 기능과는 다릅니다. 통계 데이터에 관한 문의나 삭제 요청은 아래 이메일로 연락해 주세요. 앱은 이용자의 이름·이메일과 설치 식별자를 연결해 보관하지 않으므로, 개별 설치의 데이터를 식별하기 위해 추가 정보가 필요할 수 있습니다.

---

### 9. 보안

앱은 로컬 저장 데이터 및 백업 파일 보호를 위해 보안 기능을 적용할 수 있습니다.

- 일부 민감한 설정이나 상태 정보는 보안 저장소를 활용할 수 있습니다.
- 백업 파일은 암호화 형식으로 생성될 수 있습니다.

다만 기기 보안 상태, 이용자의 비밀번호 관리, 외부 저장 위치의 보호 수준 등에 따라 실제 보호 수준은 달라질 수 있습니다.

---

### 10. 문의처

개인정보처리방침 또는 데이터 처리 방식에 관한 문의는 아래로 연락해 주세요.

- 이메일: sooyeol86@gmail.com

---

## 🇺🇸 Privacy Policy

Solid TabGroup Browser (the "App") is not primarily a server-side account or member-information collection service. Instead, it is a browser-style app that **primarily stores browsing and tab-group data on the user’s device** in order to provide session restore, tab-group management, and backup/restore features.

This policy explains what information the App may store locally on the device, why it is used, and what users should understand when opening third-party websites or external app links.

The App uses **Google AdMob advertising and Google Analytics for Firebase usage statistics**, as described below.

---

### 1. Information Stored and Processed by the App

The App may **primarily store the following information on the user’s device**:

- tab group and session information
- lists of open tabs and tab state
- visited URLs and browsing history
- app settings and preferences
- cookie information or cookie snapshots used for session restore and tab-group switching
- automatic backup files and related local restore data
- private tab-group settings and hidden tab-group list state

Depending on user actions, the following files may also be created:

- encrypted tab-group backup files (`.tbg`)
- encrypted full-backup files (`.tbbak`)

We have not identified a core App feature that sends member information or browsing data to a developer-operated server. Third-party components such as advertising SDKs may still handle information under their own policies.

---

### 2. Purpose of Use

The App uses locally stored information for the following purposes:

- opening and switching tab groups
- maintaining and restoring browsing sessions
- providing history and autocomplete
- saving app settings
- backing up and restoring tab groups or full app data
- showing tab groups in a list, reordering them, and selecting a default tab group
- hiding private tab groups and allowing re-entry by code
- handling and controlling external app links
- managing browser data such as cookies, web storage, and cache
- loading and showing banner ads
- analyzing usage statistics to improve the App

---

### 3. Storage Location and Retention Method

The above information is generally stored in the **local storage of the user’s device**.

- The App primarily keeps browsing-related data in on-device local storage.
- Generated backup files may be stored on the device or in another location selected by the user when saving or exporting them.
- We have not identified a default App feature that uploads this data to developer-operated servers for storage or review.
- Settings such as whether a tab group is private, tab-group order, and the default tab group may also be stored on the device.

---

### 4. Backup Files and Encryption

The App may provide features to back up and restore tab groups or full app data.

- When the user creates a backup, an encrypted backup file may be generated.
- Such files may be saved, moved, or exported depending on the user’s choices.
- The user is responsible for how backup files are stored, transferred, or shared.

The App may apply security measures to protect backup files, but it does not guarantee absolute security in every storage environment or external transfer path.

---

### 5. Third-Party Websites and External App Links

Because the App functions as a browser, it may communicate with websites opened by the user, and some links may open in external apps.

- When a user opens a website in the App, that website may process cookies, local storage, connection data, or similar information under its own policies.
- Some links, such as `mailto:`, `tel:`, or Kakao-related links, may be handed off to and opened in external apps.
- Information processing by third-party websites or external apps is governed by the privacy policies or terms of those services.

Accordingly, this Privacy Policy applies to **the App’s own data handling practices** and does not control or fully describe the behavior of third-party websites or external apps opened by the user.

---

### 6. Advertising, Analytics and Third-Party SDKs

The App uses **Google AdMob** for banner ads and **Google Analytics for Firebase** for usage statistics. This policy includes analytics introduced in Android and iOS version 1.0.12. Last updated: November 24, 2026.

AdMob may collect and share IP addresses and approximate location derived from them, device and advertising identifiers, app and ad interactions, crash information and performance data for advertising, analytics, diagnostics and fraud prevention. Availability of advertising identifiers depends on operating-system permissions and user settings.

Firebase Analytics measures automatic events such as app launches, sessions and engagement time, plus counts of new tabs and tab groups, to understand usage and improve the App.

- Statistics may include an app-instance identifier, app version, device model, operating system, language and approximate region derived from IP addresses. These data are transmitted to Google servers.
- The App does not set a name, email address or account user ID in Analytics. An installation identifier is still present, so these statistics should not be treated as fully anonymous.
- Analytics events do not contain visited URLs, search terms, page titles, browsing history, tab-group names or codes, cookies or backup contents.
- Custom new-tab events are excluded for private tab groups. Automatic app-launch and session statistics may still be collected while a private group is in use.
- Analytics advertising-ID collection, iOS IDFV collection and advertising-personalization signals are disabled. These settings do not disable separate processing by the AdMob advertising SDK.
- Firebase usage statistics for the Android and iOS apps are linked to the respective apps' AdMob reports to view usage and advertising performance together.

Analytics collection starts automatically after app startup. There is currently no separate in-app analytics opt-out setting. Data are encrypted in transit. Google's retention and deletion practices apply to analytics and advertising data stored by those services. Uninstalling the App or deleting local app data does not immediately delete data already transmitted.

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Privacy and Security in Firebase](https://firebase.google.com/support/privacy)
- [Google Analytics data collection](https://support.google.com/analytics/answer/11593727)

---

### 7. Sharing with Third Parties

We have not identified a default App structure that provides users’ browsing data, session data, or tab-group data to third parties through a developer-operated server.

However, information may reach external services in the following cases:

- when the user directly opens a website
- when the user launches an external app link
- when an advertising SDK processes the information it needs to load or display ads
- when Firebase Analytics collects app-usage statistics and uses them in the linked AdMob reports
- when the user manually moves or shares backup files to external services or storage locations

In those cases, the relevant information is handled according to the policies of the website, app, or storage service chosen by the user.

---

### 8. Deletion and User Controls

Users may directly manage or delete stored data through features provided in the App.

Examples of available controls may include:

- deleting current-site cookies and web storage
- deleting all cookies
- deleting all cache
- deleting all data
- deleting a tab group
- turning off the private tab-group setting
- deleting backup files directly

If backup files are stored outside the App’s own local storage area, the user may need to delete those files manually from the location where they were saved.

Private tab groups may be hidden from the chooser list, but they are not automatically deleted just because they are hidden.

You can manage ad personalization and advertising identifiers in your device's privacy and advertising settings. Changing ad settings does not turn off Analytics usage collection. For questions or requests concerning analytics data, including deletion, contact the email below. The App does not maintain a mapping between a person's name or email and an installation identifier, so additional information may be needed to identify an individual installation's data.

---

### 9. Security

The App may apply security measures to protect locally stored data and backup files.

- Some sensitive settings or state information may use secure storage.
- Backup files may be created in encrypted form.

However, the actual level of protection may vary depending on the security state of the device, the user’s password management, and the safeguards of any external storage location.

---

### 10. Contact

If you have questions about this Privacy Policy or the App’s data handling practices, please contact:

- Email: sooyeol86@gmail.com
