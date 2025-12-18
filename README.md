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
- iCAN国内予選 (https://www.kuas.ac.jp/news/2024/4/6473)

## MISC
- IEEE WCCI IJCNN Workshop "IEEE Humanitarian Activities Workshop with AI Technologies" Presenter
  - Title: "CaCo: Robot analyzing disaster victim needs and mental care during disasters"
  - Paper: https://drive.google.com/file/d/1xiAgeeBJCd2L6KPhkl4nFZCB8Gs4ojiA/view (p5-8)

## 実務経験 (インターン含む)

### 2024/8〜2025/3 株式会社ドワンゴ

#### 使用言語・ライブラリ・アーキテクチャ
- Kotlin
- Jetpack Compose (Android View)
- JUnit, Espresso (UIテスト)
- MVVM


#### 業務内容

オンライン学習プラットフォーム「Zen Study」のAndroidアプリチームに所属し、生徒の学習環境向上を目指した開発に従事しました. 大きく分けて3つのことを行いました。
- Viewで書かれたコンポーネントを段階的にJetpack Composeに置き換えること
- Deprecatedになったコンポーネントの置き換え
- 新規UIの作成および提案
 
### 2025/4〜 株式会社eMoBi

#### 使用言語・ライブラリ・アーキテクチャ
- TypeScript
- React
- Next.js (App Router)
- SWR
- Hono
- BFF

#### 使用ツール
- Github Actions
- Figma

#### 業務内容

車両貸出プラットフォーム「eMoBi Web App」のソフトウェアチームに所属し、既存モバイルアプリをベースに分散していたサービスを一つのWebアプリ化する業務に従事しました。
* 分散していたサービス: モバイルアプリに加え、別途予約システムのSaaSを導入していました

(こちらの業務内容につきましては、現時点(8月)を基準に内容を記述しています)

大きく分けて3つのことを行いました

- Webアプリの要件定義〜実装までを担当: Webアプリ化するにあたって、要件過剰だったモバイルアプリを改めて要件定義し直しデザイン等も刷新しました。

  - 既存ネイティブアプリを参考に、予約・乗車に必要最低限な機能要件の策定
  - Figmaを用いたデザインの作成
  - OpenAPIやStorybook等を導入し、ドキュメントを充実化する
  - 簡易的なアジャイル開発の導入 (リリーススパンを1週間目安にスケジュール感を調整)

- 技術面: 技術面に関しては、以下の業務を担当しました。

  - BFFアーキテクチャの導入: 既存のJavaサーバーがモバイル向けにAPIが開発されていたため、Webアプリにするにあたって必要なレスポンスの前処理等を行うBFFサーバーをHonoで記述し、NextJSのRoute Handlersに統合しました
  - useSWR/Jotaiの導入: NextJSに親和性のあるfetcherを導入し、状態管理・キャッシュ管理等を一元で行えるようにしました. また、Jotaiを用いることで不要なAPIリクエストを削減しパフォーマンスを向上させました。
  - neverthrowの導入: エラーハンドリングをtry-catchではなく、Result型を用いることでcatch漏れによる想定外挙動の回避等のヒューマンエラーを極力減らしました。
 
- 作業の自動化等
  - CIの自動化：Github Actionsを用いてMerge前にLint/Testが走るようにしました。
  - Mockの反映を高速化：Geminiを用いて議事録を要約し、機能要件をまとめたものをGithub Issuesにあげ即座にClaude Codeに実装させることで議論のスピードを向上させました。
  - 決済SaaSの一本化：複数の決済SaaSを用いて行っていたものをStripeに一本化し、各店舗の売上の集計を週次で出力するようにしました。
  - Google Tag Managerの導入: 広告流入等の効果測定を行うために導入しました。


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
