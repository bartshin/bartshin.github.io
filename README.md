<img src = "https://user-images.githubusercontent.com/65215523/116958662-8d0e6e00-acc5-11eb-85b0-9e0bdfefe6f5.png" width="120" height="120">
# Pixel scheduler 의 개인정보 정책

해당 어플리케이션은 어떠한 사용자의 정보도 수집하지 않으며 Apple의 iCloud의 서버와
Google의 Oauth, Calendar Api 서버를 제외하고는 기기 외부로 사용자의 데이터를 전송하지 않습니다.

해당 어플리케이션은 사용자의 동의 없이는 iCloud서버와 Google 서버와의 통신을 시도하지 않습니다.
사용자는 iCloud 서버와의 데이터 전송을 직접 차단할 수 있으며 언제든지 변경할 수 있습니다.

해당 어플리케이션은 외부와의 데이터 전송 또는 기기 내부의 데이터 저장 과정에서의 개발자가 의도하지 않은 데이터의 손실 또는 
외부 공격으로 인한 데이터의 노출에 대하여 책임을 지지 않습니다.

## Google Calendar의 데이터

**데이터의 요청**

해당 어플리케이션은 사용자가 명시적으로 데이터의 사용을 동의했을때에만 Google 서버에 사용자의 캘린더 정보를 요청합니다.

**데이터 요청의 목적**

Google Calendar 서버의 사용자 정보를 해당 어플리케이션에서 확인, 수정하기 위하여 요청하며 수정사항은 해당 어플리케이션에 국한됩니다.

**사용자 인증**

사용자가 데이터 사용을 오청했을시 사용자 인증을 위해 Google Oauth 로그인을 시도합니다.
Google의 Oauth 서버를 통한 로그인은 ios의 webkit 서비스를 통해 이루어지고 사용자의 계정 정보는 
해당 어플리케이션에게 허용되지 않습니다 데이터 이용을 위한 접근 토큰은 iOS의 keychain을 통해 기기 내부에 저장되며 다른 어플리케이션에서의
접근이 차단됩니다.

**데이터 처리**

구글서버로부터의 사용자의 데이터는 기기 내부에서 사용되며 사용자가 명시적으로 사용할 것을 선택하지 않은 모든 정보는 저장되지 않고 폐기됩니다.
사용자가 명시적으로 사용할 것을 선택한 정보는 기기에 저장되며 사용자가 확인할 수 있습니다 또한 사용자가 iCloud 서버으로의 데이터 저장을 
활성화 했다면 함께 저장됩니다.

# Privacy Policy of Pixel Scheduler

Bartshin built the Pixel Scheduler app as a Freemium app. This SERVICE is provided by Bartshin at no cost and is intended for use as is.

This page is used to inform visitors regarding my policies with the collection, use, and disclosure of Personal Information if anyone decided to use my Service.

If you choose to use my Service, then you agree to the collection and use of information in relation to this policy. The Personal Information that I collect is used for providing and improving the Service. I will not use or share your information with anyone except as described in this Privacy Policy.

The terms used in this Privacy Policy have the same meanings as in our Terms and Conditions, which is accessible at Pixel Scheduler unless otherwise defined in this Privacy Policy.

**Information Collection and Use**

For a better experience, while using our Service, I may require you to provide us with certain personally identifiable information, including but not limited to None. The information that I request will be retained on your device and is not collected by me in any way.

**Log Data**

I want to inform you that whenever you use my Service, in a case of an error in the app I collect data and information (through third party products) on your phone called Log Data. This Log Data may include information such as your device Internet Protocol (“IP”) address, device name, operating system version, the configuration of the app when utilizing my Service, the time and date of your use of the Service, and other statistics.

**Cookies**

Cookies are files with a small amount of data that are commonly used as anonymous unique identifiers. These are sent to your browser from the websites that you visit and are stored on your device's internal memory.

This Service does not use these “cookies” explicitly. However, the app may use third party code and libraries that use “cookies” to collect information and improve their services. You have the option to either accept or refuse these cookies and know when a cookie is being sent to your device. If you choose to refuse our cookies, you may not be able to use some portions of this Service.

**Service Providers**

I may employ third-party companies and individuals due to the following reasons:

*   To facilitate our Service;
*   To provide the Service on our behalf;
*   To perform Service-related services; or
*   To assist us in analyzing how our Service is used.

I want to inform users of this Service that these third parties have access to your Personal Information. The reason is to perform the tasks assigned to them on our behalf. However, they are obligated not to disclose or use the information for any other purpose.

**Security**

I value your trust in providing us your Personal Information, thus we are striving to use commercially acceptable means of protecting it. But remember that no method of transmission over the internet, or method of electronic storage is 100% secure and reliable, and I cannot guarantee its absolute security.

**Links to Other Sites**

This Service may contain links to other sites. If you click on a third-party link, you will be directed to that site. Note that these external sites are not operated by me. Therefore, I strongly advise you to review the Privacy Policy of these websites. I have no control over and assume no responsibility for the content, privacy policies, or practices of any third-party sites or services.

**Children’s Privacy**

These Services do not address anyone under the age of 13. I do not knowingly collect personally identifiable information from children under 13 years of age. In the case I discover that a child under 13 has provided me with personal information, I immediately delete this from our servers. If you are a parent or guardian and you are aware that your child has provided us with personal information, please contact me so that I will be able to do necessary actions.

**Changes to This Privacy Policy**

I may update our Privacy Policy from time to time. Thus, you are advised to review this page periodically for any changes. I will notify you of any changes by posting the new Privacy Policy on this page.

This policy is effective as of 2021-04-29

## Data from Google Calendar

**Request user's data**

This SERVICE will request user's data from Google Calendar service only when user initiate data request.

**Purpose of using user's data**

This app make user's data from Google Calendar visible and correctible in this app.
The alteration will not be applied to Google Calendar.

**User Authentication**

When user initiate data request this app try to login to Google Oauth.
The login process with Google Oauth is fulfilled by Webkit framework in iOS and user's account information is not allowed to this app.
The access token for authentication is stored in iOS keychain and it is not accessible for other app.

**Data management**

The user's data from Google Calendar that user not select to use in this app will be terminated.
If user choose storing data to iCloud server then the data from Google Calendar will be stored together.

**Contact Us**

If you have any questions or suggestions about my Privacy Policy, do not hesitate to contact me at bartshin@icloud.com.
