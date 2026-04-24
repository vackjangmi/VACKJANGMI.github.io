---
layout: doc
title: 쓸만한 탭그룹 브라우저 개인정보처리방침
app_title: 쓸만한 탭그룹 브라우저
app_url: /apps/tabgroup-browswer/
---

## 🇰🇷 개인정보처리방침

쓸만한 탭그룹 브라우저(이하 "앱")는 일반적인 회원정보 수집형 서비스가 아니라, 브라우징 및 탭 그룹 데이터를 **주로 이용자 기기 내부에 저장**하여 세션 복원, 탭 그룹 관리, 백업/복원 기능을 제공하는 앱입니다.

본 문서는 앱이 어떤 정보를 기기 내부에 저장할 수 있는지, 그 목적이 무엇인지, 그리고 외부 웹사이트 및 외부 앱 링크 처리 시 어떤 점을 알아두셔야 하는지를 설명합니다.

---

### 1. 앱이 저장·처리하는 정보

앱은 다음 정보를 **주로 이용자 기기 내부에 저장**할 수 있습니다.

- 탭 그룹 및 세션 정보
- 열려 있는 탭 목록과 각 탭의 상태
- 방문 URL 및 브라우징 기록
- 앱 설정값
- 세션 복원 및 탭 그룹 전환을 위한 쿠키 정보 또는 쿠키 스냅샷
- 자동 백업 파일 및 복원에 필요한 로컬 데이터

또한 이용자 동작에 따라 다음과 같은 파일이 생성될 수 있습니다.

- 암호화된 탭 그룹 백업 파일 (`.tbg`)
- 암호화된 전체 백업 파일 (`.tbbak`)

앱은 위 정보를 앱 기능 제공을 위해 기기 내부에 저장할 수 있으나, **앱 개발자가 운영하는 별도 서버로 회원정보나 브라우징 데이터를 수집하는 구조를 기본으로 하지 않습니다.**

---

### 2. 정보의 이용 목적

앱은 기기 내부에 저장된 정보를 다음 목적을 위해 사용합니다.

- 탭 그룹 열기 및 전환
- 브라우징 세션 유지 및 복원
- 방문 기록 및 자동완성 제공
- 앱 설정 저장
- 탭 그룹 백업/복원 및 전체 백업/복원
- 외부 앱 링크 처리 및 관련 제어 기능 제공
- 쿠키, 웹 저장소, 캐시 등 브라우저 데이터 관리

---

### 3. 보관 위치 및 보관 방식

위 정보는 원칙적으로 **이용자 기기 내부 저장소**에 보관됩니다.

- 앱은 브라우징 관련 데이터를 주로 로컬 저장소에 보관합니다.
- 생성된 백업 파일은 이용자가 저장 또는 내보내기한 위치에 따라 기기 내부 또는 이용자가 선택한 저장 위치에 보관될 수 있습니다.
- 앱 자체 서버에 해당 데이터를 업로드하거나 개발자가 이를 열람하는 구조를 기본 기능으로 제공하지 않습니다.

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

### 6. 제3자 제공

앱 개발자가 운영하는 별도 서버로 이용자의 브라우징 데이터, 세션 데이터, 탭 그룹 데이터 등을 **제3자에게 제공하는 구조는 기본적으로 없습니다.**

다만 다음 경우에는 정보가 외부 서비스로 전달될 수 있습니다.

- 이용자가 직접 웹사이트에 접속하는 경우
- 이용자가 외부 앱 링크를 실행하는 경우
- 이용자가 백업 파일을 외부 서비스 또는 외부 저장 위치로 직접 이동·공유하는 경우

이 경우 해당 정보 처리는 이용자가 선택한 웹사이트, 앱, 저장 서비스의 정책에 따릅니다.

---

### 7. 삭제 및 이용자 통제 방법

이용자는 앱 내 기능을 통해 저장된 데이터를 직접 관리하거나 삭제할 수 있습니다.

예를 들어 다음과 같은 기능이 제공될 수 있습니다.

- 현재 사이트 쿠키 및 웹 저장소 삭제
- 전체 쿠키 삭제
- 전체 캐시 삭제
- 전체 데이터 삭제
- 탭 그룹 삭제
- 백업 파일 직접 삭제

백업 파일이 앱 외부 저장소에 저장된 경우에는, 해당 파일을 저장한 위치에서 이용자가 직접 삭제해야 할 수 있습니다.

---

### 8. 보안

앱은 로컬 저장 데이터 및 백업 파일 보호를 위해 보안 기능을 적용할 수 있습니다.

- 일부 민감한 설정이나 상태 정보는 보안 저장소를 활용할 수 있습니다.
- 백업 파일은 암호화 형식으로 생성될 수 있습니다.

다만 기기 보안 상태, 이용자의 비밀번호 관리, 외부 저장 위치의 보호 수준 등에 따라 실제 보호 수준은 달라질 수 있습니다.

---

### 9. 문의처

개인정보처리방침 또는 데이터 처리 방식에 관한 문의는 아래로 연락해 주세요.

- 이메일: sooyeol86@gmail.com

---

## 🇺🇸 Privacy Policy

Solid TabGroup Browser (the "App") is not primarily a server-side account or member-information collection service. Instead, it is a browser-style app that **primarily stores browsing and tab-group data on the user’s device** in order to provide session restore, tab-group management, and backup/restore features.

This policy explains what information the App may store locally on the device, why it is used, and what users should understand when opening third-party websites or external app links.

---

### 1. Information Stored and Processed by the App

The App may **primarily store the following information on the user’s device**:

- tab group and session information
- lists of open tabs and tab state
- visited URLs and browsing history
- app settings and preferences
- cookie information or cookie snapshots used for session restore and tab-group switching
- automatic backup files and related local restore data

Depending on user actions, the following files may also be created:

- encrypted tab-group backup files (`.tbg`)
- encrypted full-backup files (`.tbbak`)

The App may store this information locally to provide its features, but it **is not designed as a service that primarily collects member information or browsing data to servers operated by the developer.**

---

### 2. Purpose of Use

The App uses locally stored information for the following purposes:

- opening and switching tab groups
- maintaining and restoring browsing sessions
- providing history and autocomplete
- saving app settings
- backing up and restoring tab groups or full app data
- handling and controlling external app links
- managing browser data such as cookies, web storage, and cache

---

### 3. Storage Location and Retention Method

The above information is generally stored in the **local storage of the user’s device**.

- The App primarily keeps browsing-related data in on-device local storage.
- Generated backup files may be stored on the device or in another location selected by the user when saving or exporting them.
- The App does not provide a default feature that uploads this data to the developer’s own servers for storage or review.

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

### 6. Sharing with Third Parties

The App does **not** have a default structure in which the developer provides users’ browsing data, session data, or tab-group data to third parties through a separate developer-operated server.

However, information may reach external services in the following cases:

- when the user directly opens a website
- when the user launches an external app link
- when the user manually moves or shares backup files to external services or storage locations

In those cases, the relevant information is handled according to the policies of the website, app, or storage service chosen by the user.

---

### 7. Deletion and User Controls

Users may directly manage or delete stored data through features provided in the App.

Examples of available controls may include:

- deleting current-site cookies and web storage
- deleting all cookies
- deleting all cache
- deleting all data
- deleting a tab group
- deleting backup files directly

If backup files are stored outside the App’s own local storage area, the user may need to delete those files manually from the location where they were saved.

---

### 8. Security

The App may apply security measures to protect locally stored data and backup files.

- Some sensitive settings or state information may use secure storage.
- Backup files may be created in encrypted form.

However, the actual level of protection may vary depending on the security state of the device, the user’s password management, and the safeguards of any external storage location.

---

### 9. Contact

If you have questions about this Privacy Policy or the App’s data handling practices, please contact:

- Email: sooyeol86@gmail.com
