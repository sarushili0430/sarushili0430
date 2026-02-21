# Hi there 👋
My name is Koyu Fuke, currently at my 3rd year in Kyoto University of Advanced Science. Mainly coding for modern applications, written in TypeScript, Dart, Kotlin.

<!----
![LGTM](https://image.lgtmoon.dev/271767)
---->

## Skills
[![My Skills](https://skillicons.dev/icons?i=kotlin,flutter,typescript,nextjs,react,vscode,androidstudio)](https://skillicons.dev)

## Contact
[![Discord](https://skillicons.dev/icons?i=discord)](https://discordapp.com/users/515325909851439109)
[![Instagram](https://skillicons.dev/icons?i=instagram)](https://www.instagram.com/k.fuke0502/profilecard/?igsh=ZHpiamlubzcxZHJo)
[![LinkedIn](https://skillicons.dev/icons?i=linkedin)](https://www.linkedin.com/in/koyu-fuke-70a683264)

## Stats
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=sarushili0430&bg_color=181b1f&text_color=aeaeae&title_color=fff7ed&icon_color=fff7ed)](https://github.com/sarushili0430/sarushili0430)

## Awards
- iCAN Domestic Preliminary Round ([link](https://www.kuas.ac.jp/news/2024/4/6473))

## MISC
- IEEE WCCI IJCNN Workshop "IEEE Humanitarian Activities Workshop with AI Technologies" Presenter
  - Title: "CaCo: Robot analyzing disaster victim needs and mental care during disasters"
  - Paper: [link](https://drive.google.com/file/d/1xiAgeeBJCd2L6KPhkl4nFZCB8Gs4ojiA/view) (p5-8)

## Work Experience (including internships)

### Aug 2024 – Mar 2025: DWANGO Co., Ltd.

#### Languages, Libraries & Architecture
- Kotlin
- Jetpack Compose (Android View)
- JUnit, Espresso (UI Testing)
- MVVM

#### Job Description
I was part of the Android app team for the online learning platform "Zen Study," working on development aimed at improving the learning environment for students. My work broadly fell into three areas:
- Incrementally migrating components written in View to Jetpack Compose
- Replacing deprecated components
- Creating and proposing new UI elements

### Apr 2025 – Present: eMoBi, Inc.

#### Languages, Libraries & Architecture
- TypeScript
- React
- Next.js (App Router)
- SWR
- Hono
- BFF

#### Tools
- GitHub Actions
- Figma

#### Job Description
I was part of the software team for the vehicle rental platform "eMoBi Web App," working on consolidating previously distributed services—based on the existing mobile app—into a single web application.

> Distributed services: In addition to the mobile app, a separate reservation system SaaS had been adopted.
>
> (The job description below is written as of August.)

My work broadly fell into three areas:

- **Requirements definition through implementation of the web app:** When transitioning to a web app, I redefined the requirements of the mobile app (which had been over-specified) and refreshed the design.
  - Defined the minimum necessary functional requirements for booking and ride operations, referencing the existing native app
  - Created designs using Figma
  - Introduced OpenAPI, Storybook, and other tools to enrich documentation
  - Introduced lightweight agile development (adjusting schedules to target a one-week release cadence)

- **Technical work:**
  - **Introduced BFF architecture:** Since the existing Java server had APIs built for mobile, I wrote a BFF server in Hono to handle response preprocessing needed for the web app and integrated it into Next.js Route Handlers.
  - **Introduced useSWR/Jotai:** Adopted a fetcher with good Next.js compatibility to centralize state and cache management. Also used Jotai to reduce unnecessary API requests and improve performance.
  - **Introduced neverthrow:** Replaced try-catch error handling with a Result type to minimize human errors such as unexpected behavior from missed catches.

- **Workflow automation, etc.**
  - **CI automation:** Set up GitHub Actions to run lint/tests before merges.
  - **Faster mock implementation:** Used Gemini to summarize meeting notes and compile feature requirements into GitHub Issues, then had Claude Code implement them immediately to speed up discussions.
  - **Consolidated payment SaaS:** Unified multiple payment SaaS providers into Stripe and set up weekly revenue reports per store.
  - **Introduced Google Tag Manager:** Implemented for measuring the effectiveness of ad-driven traffic.


<!--
**sarushili0430/sarushili0430** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
