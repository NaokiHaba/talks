---
title: OSS活動で世界とつながる
info: |
  OSS活動を通じたエンジニアの成長と世界とのつながり
  Presented by NaokiHaba
class: text-center
transition: 'slide'
mdc: true
css: unocss
---


<h1 class="!text-12">OSS活動で世界とつながる</h1>

<span bg-black:10 rounded px1 op75>
2025-03-19
</span>

<!--
みなさん、こんにちは！

本日は、私が実際に経験したOSS活動について、その始め方や得られた経験、そして成長についてお話しさせていただきます。

普段の業務とは少し異なる、エンジニアとしての新しい挑戦について、一緒に考えていければと思います。
-->

---
layout: intro
class: pl-30
---


# Naoki Haba

<img src="https://github.com/NaokiHaba.png" rounded-full w-40 abs-tr mt-16 mr-12/>


<div class="[&>*]:important-leading-10 opacity-80">

- VueFes Japan Core Staff
- VueUse Collaborator
- Pinia・Vee-validate Contributor
- NestJS Japan User Group Owner

</div>

<!--
まずは自己紹介をします。

私の名前は、羽馬直樹です。

Pinia・Vee-validate・VueUse といった Vue.js に関連する OSS に貢献しています。

また、Vue.js-JP のコアスタッフ・NestJS Japan User Group のオーナーを務めています。

それでは、始めて行きましょう！

-->

---
layout: center
---

<div class="mb-8">
  <span class="bg-yellow-500 text-black px-4 py-2 rounded-full text-xl font-bold">⚠️ 注意点・前提</span>
</div>

<div class="p-4 text-3xl">

- 今日話すことは、あくまで個人の見解です
- OSSへの貢献を強制するものではありません
- OSS活動はエンジニアの成長につながる1つの手段です
- あくまでも参考にしていただければ幸いです
</div>

<!--
本日のお話の前に、いくつか注意点をお伝えさせていただきます。

まず、これから私がお話しする内容は、あくまでも個人の経験と見解に基づくものです。

OSSへの貢献は、エンジニアとしての成長につながる「選択肢の1つ」です。
決してOSS活動が成長への唯一の道ではありません。

様々な成長の形がある中で、今日は私がOSS活動を通じて得られた経験や学びをお伝えできればと思います。

それでは、本題に入っていきましょう。
-->

---
layout: center
---

<h1>OSSとは</h1>

<!--
まずは、OSSの定義についてお話しさせていただきます。
-->


---
layout: center
---

<div class="flex flex-col items-center justify-center gap-8">
  <div class="text-3xl font-bold mb-8">
    OSSの3つの特徴
  </div>

  <div class="grid gap-6 text-2xl">
    <div class="flex items-center gap-4">
      <div><strong>ソースコードが公開</strong>されているソフトウェア</div>
    </div>
    <div class="flex items-center gap-4">
      <div><strong>誰でも自由に使用・改変・再配布</strong>できる</div>
    </div>
    <div class="flex items-center gap-4">
      <div><strong>コミュニティ主導の開発</strong>（世界中の開発者が協力）</div>
    </div>
    <div class="flex items-center gap-4">
      <div><strong>代表的なOSS</strong></div>
      <div>Linux・Vue.js・Golang・PHPなど</div>
    </div>
  </div>
</div>

<!--
OSSには3つの重要な特徴があります。

1つ目は、ソースコードが公開されているということです。
誰でもコードを読むことができ、どのように動作しているかを確認できます。

2つ目は、自由な利用と改変が可能ということです。
必要に応じて機能を追加したり、バグを修正したりすることができます。

3つ目は、コミュニティ主導の開発スタイルです。
世界中の開発者が協力して、より良いソフトウェアを作り上げています。

Linux、Vue.js、Golang、PHPなど、私たちが日常的に使用している多くのソフトウェアもOSSです。
-->

---
layout: center
---

<h1>私たちは日々OSSの恩恵を受けている</h1>

<!--
つまり、私たちは日々の開発でOSSの恩恵を受けているのです。
-->


---
layout: center
---

<h1>OSSへの貢献</h1>

<!-- 
OSSへの貢献は、エンジニアとしての成長につながる「選択肢の1つ」です。

ここからは、OSSへの貢献についてお話しさせていただきます。
 -->

---
layout: center
---

<div class="flex flex-col items-center justify-center gap-12">
  <div class="text-4xl font-bold mb-8">
    OSSへの貢献方法
  </div>

  <div class="grid grid-cols-2 gap-16">
    <div class="flex flex-col items-center gap-6 p-8 bg-gray-50 rounded-xl shadow-sm hover:shadow-md transition-shadow">
      <div class="text-5xl">💻</div>
      <div class="text-3xl font-bold text-sky-500">技術的な貢献</div>
      <div class="text-xl text-gray-600">
        - 機能追加<br>
        - バグ修正<br>
        - ドキュメント改善<br>
        - テストコード作成<br>
        - プロジェクト管理
        - バージョン管理
      </div>
    </div>
    <div class="flex flex-col items-center gap-6 p-8 bg-gray-50 rounded-xl shadow-sm hover:shadow-md transition-shadow">
      <div class="text-5xl">🌱</div>
      <div class="text-3xl font-bold text-sky-500">コミュニティへの貢献</div>
      <div class="text-xl text-gray-600">
        - OSSへの貢献<br>
        - イベント運営<br>
        - 勉強会開催<br>
        - カンファレンス参加<br>
      </div>
    </div>
  </div>
</div>

<!--
OSSへの貢献方法は、大きく2つに分けられます。

1つ目は「コードを書く」という直接的な貢献です。

主に、機能追加やバグ修正、ドキュメントの改善、テストコードの作成などが含まれます。

2つ目は「コミュニティを育てる」という間接的な貢献です。

主に、イベントの運営や勉強会の開催、カンファレンスへの参加やスタッフとしての活動などが含まれます。

どちらの貢献も、OSSの発展には欠かせない重要な要素です。

それでは、具体的な貢献方法についてお話しさせていただきます。
-->

---
layout: center
---

<div class="flex flex-col items-center justify-center gap-8">
  <div class="text-4xl font-bold text-sky-500 mb-4">
    技術的な貢献
  </div>
  <div class="grid grid-cols-2 gap-8 w-full max-w-4xl">
    <div class="space-y-6 p-6 bg-sky-50 rounded-xl shadow-sm">
      <div class="text-2xl font-bold text-sky-700">開発面 💻</div>
      <ul class="space-y-3 text-xl text-gray-700">
        <li class="flex items-center gap-2">
          <span class="text-green-600">●</span> 新規機能の開発
        </li>
        <li class="flex items-center gap-2">
          <span class="text-red-600">●</span> バグの修正
        </li>
        <li class="flex items-center gap-2">
          <span class="text-blue-600">●</span> 機能改善
        </li>
        <li class="flex items-center gap-2">
          <span class="text-purple-600">●</span> テストコードの追加
        </li>
      </ul>
    </div>
    <div class="space-y-6 p-6 bg-sky-50 rounded-xl shadow-sm">
      <div class="text-2xl font-bold text-sky-700">ドキュメント面 📚</div>
      <ul class="space-y-3 text-xl text-gray-700">
        <li class="flex items-center gap-2">
          <span class="text-yellow-600">●</span> ドキュメントの改善
        </li>
        <li class="flex items-center gap-2">
          <span class="text-orange-600">●</span> チュートリアル作成
        </li>
        <li class="flex items-center gap-2">
          <span class="text-pink-600">●</span> RFC作成
        </li>
        <li class="flex items-center gap-2">
          <span class="text-indigo-600">●</span> プロジェクト管理
        </li>
      </ul>
    </div>
  </div>
  <div class="mt-8 p-4 bg-amber-50 rounded-lg text-lg text-amber-900 border border-amber-200">
    <div class="flex items-center gap-2">
      <span class="text-2xl">💡</span>
      <span>これらの貢献により、私たちは日々安定したOSSを利用できています</span>
    </div>
  </div>
</div>

<!--
技術的な貢献について、具体的にご説明させていただきます。

開発面では、新規機能の開発やバグ修正、機能改善、テストコードの追加など、
直接的にコードに関わる貢献があります。

ドキュメント面では、ドキュメントの改善やチュートリアルの作成、
新機能の提案（RFC）、プロジェクト全体の管理など、
開発をサポートする重要な貢献があります。

これらの貢献があってこそ、私たちは日々安定してOSSを利用することができています。
OSSの開発チームの努力には、常にリスペクトを持って接するべきですね。
-->


---
layout: center
---

<div class="flex flex-col items-center justify-center gap-8">
  <div class="text-4xl font-bold text-sky-500 mb-4">
    コミュニティへの貢献
  </div>

  <div class="grid grid-cols-2 gap-8 w-full max-w-4xl">
    <div class="space-y-6 p-6 bg-sky-50 rounded-xl shadow-sm">
      <div class="text-2xl font-bold text-sky-700">開発サポート 🔧</div>
      <ul class="space-y-3 text-xl text-gray-700">
        <li class="flex items-center gap-2">
          <span class="text-green-600">●</span> 新規機能開発
        </li>
        <li class="flex items-center gap-2">
          <span class="text-red-600">●</span> バグ修正
        </li>
        <li class="flex items-center gap-2">
          <span class="text-blue-600">●</span> ドキュメント改善
        </li>
        <li class="flex items-center gap-2">
          <span class="text-purple-600">●</span> イシュー管理（トリアージ）
        </li>
      </ul>
    </div>
    <div class="space-y-6 p-6 bg-sky-50 rounded-xl shadow-sm">
      <div class="text-2xl font-bold text-sky-700">コミュニティ活動 👥</div>
      <ul class="space-y-3 text-xl text-gray-700">
        <li class="flex items-center gap-2">
          <span class="text-yellow-600">●</span> カンファレンススタッフ
        </li>
        <li class="flex items-center gap-2">
          <span class="text-orange-600">●</span> MeetUp開催
        </li>
        <li class="flex items-center gap-2">
          <span class="text-pink-600">●</span> ブログ執筆・登壇
        </li>
        <li class="flex items-center gap-2">
          <span class="text-indigo-600">●</span> スポンサー支援
        </li>
      </ul>
    </div>
  </div>
  <div class="mt-8 p-4 bg-amber-50 rounded-lg text-lg text-amber-900 border border-amber-200">
    <div class="flex items-center gap-2">
      <span class="text-2xl">💡</span>
      <span>コードを書くこと以外にも、さまざまな形でOSSに貢献できます</span>
    </div>
  </div>
</div>

<!--
コミュニティへの貢献について、具体的にご説明させていただきます。

開発サポートでは、新規機能の開発やバグ修正、ドキュメントの改善、
イシュー管理など、開発チームと同じように貢献することができます。

また、コミュニティ活動としては、カンファレンスのスタッフ参加や
MeetUpの開催、ブログ執筆、登壇活動、スポンサー支援など、
さまざまな形で貢献することができます。

このように、OSSへの貢献は必ずしもコードを書くことだけではありません。
それぞれができる形で貢献していくことが、OSSの発展につながっていきます。
-->

---
layout: center
---

<h1>OSS活動のメリット</h1>

<!-- 
OSS活動の方法がわかったところで、具体的にOSS活動のメリット・始め方についてお話しさせていただきます。
 -->

---
layout: center
---

<div class="flex flex-col items-center justify-center gap-8">
  <div class="text-4xl font-bold text-sky-500 mb-4">
    OSS活動のメリット
  </div>

  <div class="grid grid-cols-3 gap-8 w-full max-w-6xl">
    <div class="space-y-6 p-6 bg-sky-50 rounded-xl shadow-sm">
      <div class="text-2xl font-bold text-sky-700">スキルアップ 📚</div>
      <ul class="space-y-3 text-lg text-gray-700">
        <li class="flex items-start gap-2">
          <span class="text-green-600 mt-1">●</span> 世界中の開発者のコードに触れる
        </li>
        <li class="flex items-start gap-2">
          <span class="text-green-600 mt-1">●</span> 実装の詳細を理解できる
        </li>
        <li class="flex items-start gap-2">
          <span class="text-green-600 mt-1">●</span> フレームワークへの深い理解
        </li>
      </ul>
    </div>
    <div class="space-y-6 p-6 bg-sky-50 rounded-xl shadow-sm">
      <div class="text-2xl font-bold text-sky-700">キャリア形成 💼</div>
      <ul class="space-y-3 text-lg text-gray-700">
        <li class="flex items-start gap-2">
          <span class="text-blue-600 mt-1">●</span> ポートフォリオの構築
        </li>
        <li class="flex items-start gap-2">
          <span class="text-blue-600 mt-1">●</span> 技術力の可視化
        </li>
        <li class="flex items-start gap-2">
          <span class="text-blue-600 mt-1">●</span> トップ開発者との交流
        </li>
      </ul>
    </div>
    <div class="space-y-6 p-6 bg-sky-50 rounded-xl shadow-sm">
      <div class="text-2xl font-bold text-sky-700">人脈形成 🤝</div>
      <ul class="space-y-3 text-lg text-gray-700">
        <li class="flex items-start gap-2">
          <span class="text-purple-600 mt-1">●</span> グローバルな交流
        </li>
        <li class="flex items-start gap-2">
          <span class="text-purple-600 mt-1">●</span> コミュニティでの活動
        </li>
        <li class="flex items-start gap-2">
          <span class="text-purple-600 mt-1">●</span> 技術的な議論の機会
        </li>
      </ul>
    </div>
  </div>

  <div class="mt-8 p-4 bg-amber-50 rounded-lg text-lg text-amber-900 border border-amber-200">
    <div class="flex items-center gap-2">
      <span class="text-2xl">💡</span>
      <span>OSS活動は、エンジニアとしての総合的な成長につながります</span>
    </div>
  </div>
</div>

<!--
OSS活動のメリットについて、3つの観点からご説明させていただきます。

1つ目は「スキルアップ」です。
世界中の優れた開発者が書いたコードに触れることで、技術力を向上させることができます。
また、普段何気なく使用している機能の実装を理解することで、より深い知識を得ることができます。

2つ目は「キャリア形成」です。
OSSへの貢献は、自身の技術力を示す良いポートフォリオとなります。
実際のプロジェクトでの経験は、キャリアの上でも大きな価値があります。

3つ目は「人脈形成」です。
世界中の開発者と交流することで、グローバルな人脈を築くことができます。
また、コミュニティ活動を通じて、さまざまな技術的な議論に参加する機会も得られます。

このように、OSS活動には多くの学びと成長の機会が含まれています。
-->

---
layout: center
---

<h1>OSS活動の始め方</h1>

<!-- 
OSS活動のメリットがわかったところで、具体的にOSS活動を始める方法についてお話しさせていただきます。
 -->

---
layout: center
---

<div class="flex flex-col items-center justify-center gap-8">
  <div class="text-4xl font-bold text-sky-500 mb-4">
    OSS活動の始め方
  </div>
  <div class="grid grid-cols-3 gap-8 w-full max-w-6xl">
    <div class="space-y-6 p-6 bg-sky-50 rounded-xl shadow-sm hover:shadow-md transition-all">
      <div class="text-2xl font-bold text-sky-700 flex items-center gap-2">
        <span class="text-3xl">1️⃣</span> 興味のあるOSSを探す
      </div>
      <ul class="space-y-3 text-lg text-gray-700">
        <li class="flex items-start gap-2">
          <span class="text-green-600 mt-1">●</span> 普段使用しているツール
        </li>
        <li class="flex items-start gap-2">
          <span class="text-green-600 mt-1">●</span> 気になるフレームワーク
        </li>
      </ul>
    </div>
    <div class="space-y-6 p-6 bg-sky-50 rounded-xl shadow-sm hover:shadow-md transition-all">
      <div class="text-2xl font-bold text-sky-700 flex items-center gap-2">
        <span class="text-3xl">2️⃣</span> 小さな貢献から始める
      </div>
      <ul class="space-y-3 text-lg text-gray-700">
        <li class="flex items-start gap-2">
          <span class="text-blue-600 mt-1">●</span> タイプミスの修正
        </li>
        <li class="flex items-start gap-2">
          <span class="text-blue-600 mt-1">●</span> ドキュメントの改善
        </li>
        <li class="flex items-start gap-2">
          <span class="text-blue-600 mt-1">●</span> Good First Issue に挑戦
        </li>
      </ul>
    </div>
    <div class="space-y-6 p-6 bg-sky-50 rounded-xl shadow-sm hover:shadow-md transition-all">
      <div class="text-2xl font-bold text-sky-700 flex items-center gap-2">
        <span class="text-3xl">3️⃣</span> コミュニティに参加
      </div>
      <ul class="space-y-3 text-lg text-gray-700">
        <li class="flex items-start gap-2">
          <span class="text-purple-600 mt-1">●</span> Discordに参加
        </li>
        <li class="flex items-start gap-2">
          <span class="text-purple-600 mt-1">●</span> 勉強会やイベントに参加
        </li>
      </ul>
    </div>
  </div>
  <div class="mt-8 p-4 bg-amber-50 rounded-lg text-lg text-amber-900 border border-amber-200">
    <div class="flex items-center gap-2">
      <span class="text-2xl">💡</span>
      <span>大きな貢献をいきなり始めるのは難しいですが、小さな貢献から始めることで、徐々にOSS活動に慣れていくことができます。</span>
    </div>
  </div>
</div>

<!--
OSS活動の始め方について、3つのステップでご説明させていただきます。

1つ目は「興味のあるOSSを探す」ことです。
普段使用しているツールや気になるフレームワークから始めると、
モチベーションを維持しやすく、理解も深まりやすいです。

2つ目は「小さな貢献から始める」ことです。
タイプミスの修正やドキュメントの改善など、小さな貢献から始めることで、
OSSへの貢献の流れを理解することができます。

3つ目は「コミュニティに参加する」ことです。
DiscordやGitHub Discussions、勉強会などに参加することで、
他の開発者との交流が生まれ、新しい学びの機会を得ることができます。

外の世界を見ることで、新しい視点や気づきを得ることができます。
まずは小さな一歩から始めてみましょう。
-->

---
layout: center
---

<div class="flex flex-col items-center justify-center">
  <div class="text-5xl font-bold mb-16">
    Good First Issue
  </div>

  <div class="max-w-3xl text-2xl leading-relaxed space-y-12">
    <p>
      Good First Issue は、OSSプロジェクトで初めて貢献する人向けに用意された課題です。
      初心者でも取り組みやすい難易度で、詳しい説明が付いているのが特徴です。
    </p>
    <p>
      多くの場合、メンターがサポートしてくれるため、安心して取り組むことができます。
      これは、新しい貢献者を歓迎するOSSコミュニティの文化を表しています。
    </p>
    <div class="flex items-center justify-center gap-4 bg-sky-50 p-6 rounded-xl">
      <span class="text-3xl">🔍</span>
      <a href="https://goodfirstissue.dev" target="_blank" class="text-sky-600 hover:text-sky-700">
        goodfirstissue.dev で探してみましょう
      </a>
    </div>
  </div>
</div>

<!--
Good First Issueは、OSSコミュニティの重要な文化の一つです。

初めての貢献者が躊躇することなく参加できるよう、コミュニティが意図的に
用意している入り口といえます。

実際に貢献することで、OSSの開発フローを学び、コミュニティの一員として
成長していくことができます。
-->

---
layout: center
---

<div class="flex flex-col items-center justify-center gap-12">
  <div class="text-5xl font-bold text-sky-500">
    まとめ
  </div>

  <div class="grid gap-8 max-w-3xl">
    <div class="p-6 bg-sky-50 rounded-xl shadow-sm">
      <div class="text-2xl leading-relaxed space-y-6">
        <div class="flex items-center gap-3">
          <span class="text-3xl">🌱</span>
          <span class="text-gray-700">OSS活動は、エンジニアとしての成長につながる選択肢の1つです</span>
        </div>
        <div class="flex items-center gap-3">
          <span class="text-3xl">🎯</span>
          <span class="text-gray-700">自分のペースで無理なく始めることが大切です</span>
        </div>
        <div class="flex items-center gap-3">
          <span class="text-3xl">⏰</span>
          <span class="text-gray-700">時間的・精神的余裕がある時に取り組みましょう</span>
        </div>
      </div>
    </div>
  </div>
  <div class="mt-8 text-3xl font-bold text-sky-600">
    ぜひ、OSS活動を始めてみてください！
  </div>
</div>

<!--
本日のお話をまとめさせていただきます。

OSS活動は、エンジニアとしての成長につながる選択肢の1つです。
ただし、これは決して強制されるものではありません。

大切なのは、自分のペースで無理なく始めることです。
小さな貢献から始めて、徐々にステップアップしていきましょう。

時間的・精神的な余裕がある時に取り組むことで、より充実した活動ができます。

皆さんも、ぜひOSS活動を始めてみてください。
新しい発見と成長の機会が待っています。

ご清聴ありがとうございました。
-->
