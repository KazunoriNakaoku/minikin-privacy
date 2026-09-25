---
title: プライバシーポリシー | ミニマムキングダム
description: ミニマムキングダム（Minimum Kingdom）のプライバシーポリシー
---

# プライバシーポリシー / Privacy Policy

**ミニマムキングダム（Minimum Kingdom）**

最終更新日: 2026年9月25日

---

[サポート・よくある質問はこちら](./support.html)

---

## 日本語

### 1. はじめに

本ポリシーは、ミニマムキングダム（以下「本アプリ」）における利用者の情報の
取り扱いについて説明するものです。

### 2. 開発者が収集する情報

**氏名・電話番号・住所などの個人情報を入力していただく機能はありません。**

**はじめの物語を終えて王国名を決めると**、その王国名と匿名の識別子を
開発者のサーバー（Google Firebase）で扱います（第4章）。オンライン対戦・
友だち対戦・交流をご利用の場合は、さらに必要な情報を扱います。

**はじめの物語を終える前にも、以下の通信を行います。** いずれも、第4章の
匿名の識別子や利用者が入力した王国名を送るものではありません。ただし、
インターネットに接続する以上、IPアドレスは接続先に伝わります。また、
Google のサービス（Firebase・AdMob）は、その仕組み上、端末ごとの識別子を
扱うことがあります（第6章）。

- **更新の確認**: 起動のたびに、アプリの更新が必要かどうかを開発者の
  サーバー（Google Firebase）へ問い合わせます。利用者を識別しない読み取り
  だけを行います。
- **広告の準備**: 起動のたびに、最初の画面が出たあと Google の広告サービス
  （AdMob）へ接続し、広告の読み込みを始めます。はじめて起動したときは、
  iOS のトラッキングの許可を求めるダイアログと、該当地域の同意画面も
  このときに表示されます（第6章）。
- **王国名の空き確認**: 王国名を決める画面を開いたとき、「おまかせ」で出す
  候補の名前がすでに使われていないかを開発者のサーバーへ問い合わせます。
  送るのはアプリが自動で作った候補の名前だけで、**利用者が入力した名前は
  送りません**。

**はじめの物語を終えたあとは**、これに加えて、起動のときにサーバーへ接続
できるかどうかを確かめます（送る中身は空で、識別子は含みません）。

これらはアプリを動かすために必要な通信で、個別に停止する設定はありません。
広告の表示内容は第6章の方法で変更できます。

**これとは別に、王国名を決めたあとは、アプリの使われ方の大まかな集計を
送ります**（第4章「利用状況の集計」）。アカウント連携の有無にかかわらず
送られます。

### 3. 端末内に保存される情報

以下は利用者の端末内に保存され、アプリを削除すると消去されます。

- CPU対戦の勝利回数（難易度ごと）
- 出陣コスト（スタミナ）の残量と回復時刻
- チーム編成の内容
- ユニットの解放の進捗
- 王国名（表示名）とアプリの初回設定が済んだかどうかの印

**アカウントを連携している場合は、上のうち初回設定の印を除く4つが、
引き継ぎのためサーバーにも保存されます**（第4章「アカウント連携」）。
なお王国名は、連携の有無にかかわらずサーバーに保存されます（第4章）。

### 4. サーバーで扱う情報（王国名・オンライン対戦・友だち対戦）

**はじめの物語を終えて王国名を決めたとき**、または対戦機能を初めて
ご利用になるとき、利用者を識別するための**匿名の識別子**（ランダムな
文字列。氏名やメールアドレスとは結び付きません）が自動的に作られ、
以下の情報とともにサーバーへ保存されます。

- 匿名の識別子
- **王国名（表示名）**: 対戦相手の画面に表示されます（第5章）
- **コインの残高と、ログインボーナスを受け取った日付**（受け取りの重複を
  防ぐために保存します。30日を過ぎたものは自動的に消えます）
- **獲得したアイコン・フレーム・ユニット**（重複の判定と、引けるものが
  残っているかの表示に使います）
- **ガチャを引いた回数**（不具合の調査と統計のために記録します）
- 国家戦力（レート）と対戦の記録（対局の手順・勝敗・日時。人どうしのランク戦では、
  対戦した両者の王国名と使った編成も含みます）
- 対戦中の接続状態（在席）

対戦の記録は、不正な操作の検出と問い合わせ対応のために保存します。

#### 利用状況の集計

アプリのどの機能が使われているか、どこで詰まっているかを知り、改善に
役立てるため、**日付ごとの大まかな回数**をサーバーへ送ります。**王国名を
決めて匿名の識別子ができたあとに限り**、その識別子と結び付けて保存します。

送るのは次の回数だけです。

- アプリを開いた回数
- CPU対戦を始めた・勝った・決着した回数（難易度ごと）
- 合言葉対戦に入った回数
- 交流を開いた回数・発言した回数
- 編成を開いた回数
- 出陣コスト（スタミナ）が足りずに遊べなかった回数
- ランク戦が成立した・決着した・途中で終わった回数（終わった理由の内訳）
- そのとき動いていたアプリのバージョン
- その日に最後に記録した時刻（同じ日の送り直しを見分けるために使います）

**次のものは含みません。** 端末の識別子・広告識別子・機種・OS のバージョン・
位置情報・画面ごとの滞在時間・押したボタンの種類・盤面の操作・王国名・
チャットの本文。**上に挙げたもの以外は送っていません。**

**広告や宣伝には利用せず、第三者へ提供することもありません。** また、
**この集計だけを止める設定はありません**（上に挙げたもの以外を含まないため、
個別の停止設定を設けていません）。

保存期間は次のとおりです。

- **日付ごとの回数は90日で自動的に削除**されます
- **月ごとの人数の集計**（「その月に初めて記録が届いた人数」「その月に
  遊んだ人数」など、**個人と結び付かない数だけ**）は期限を定めずに残します
- **「初めて記録が届いた日」と「どの機能を使ったことがあるかの印」**は、
  同じ人を二重に数えないために必要なので、**退会まで残します**

退会（下記）では、日付ごとの回数・初めて記録が届いた日・使ったことがあるかの
印を**すべて削除**します。月ごとの人数の集計は個人と結び付かないため残ります。

#### アカウント連携（任意）

「その他」→「アカウント設定」から、Apple または Google のアカウントを
連携すると、機種変更やアプリの入れ直しの際にデータを引き継げます。
**連携は任意で、行わなくてもすべての機能をご利用いただけます。**

連携すると、認証サービス（Firebase Authentication）が Apple / Google から
受け取った識別子とメールアドレスを保存します。あわせて、**第3章に挙げた
端末内のデータ（CPU対戦の勝利回数・スタミナ・チーム編成・ユニットの解放の
進捗）と連携した日時**を、引き継ぎのためサーバーへ保存します。Apple の
「メールを非公開」をお使いの場合、開発者に届くのは転送用のアドレスのみです。
メールアドレスを広告・宣伝の目的で利用することはありません。

#### 退会（データの削除）

「その他」→「アカウント設定」→「アカウントを削除」から、アカウントとサーバー上の
データを削除できます。上記の「利用状況の集計」のうち、個人と結び付くもの
（日付ごとの回数・初めて記録が届いた日・使ったことがあるかの印）も
このとき削除されます。ただし**ランク戦（オンライン対戦）の記録は、不正な操作の
検出と問い合わせ対応のため削除の対象になりません**。記録には対戦した側の識別子と
使った編成が期限を定めず残り、人どうしの対戦では対戦時に表示された両者の王国名も
残ります（対戦相手側の記録でもあるためです）。通報した相手と以後マッチングしない
ための記録（双方の識別子のみ）も残ります。また、退会の直後に
残高が作り直されるのを防ぐため、**退会した時刻の記録**が残ります。
削除されるもの・残るものの一覧と、アプリから削除できない場合の依頼方法は
[アカウントとデータの削除](./account-deletion.html) をご覧ください。

#### 交流（ロビーチャット）

「交流」は、利用者どうしが短いメッセージを交わし、対戦を募集できる
共有の場です。ご利用の際は以下の情報がサーバーへ保存され、**他の利用者の
画面に表示されます**。

- 投稿の本文・王国名・アイコン・投稿時刻・国家戦力
- 対戦募集の場合は、募集の一言と募集の状態（募集中・締切など）
- 募集に応募した場合は、王国名と国家戦力が**募集した方の画面に**表示されます

対戦募集と応募には**チーム編成の内容**も保存されますが、一覧には表示されず、
対戦が成立した時点で相手に渡ります（通常の対戦と同じ扱いです）。

投稿は**24時間で自動的に削除**されます（最新100件のみ保持）。削除された
投稿についても、通報への対応のため本文の写しをサーバー内部で最長7日間
保存します（他の利用者には表示されません）。投稿が通報された場合は、
本文の写しを通報記録として対応の完了まで保存し、完了後に削除します。
投稿そのものに利用者の識別子（uid）は含まれません（uid の代わりに、
投稿者ごとに固定の匿名の印を含みます）。**通報対応のための写しには uid を
含みます**（他の利用者には表示されません）。

不適切な投稿への対策として、入力時のフィルタ・投稿の長押しからの通報・
通報した相手の投稿の非表示・運営による投稿の削除を行っています。
初回利用時に利用ルールへの同意をお願いしています。

#### お知らせ（プッシュ通知）

対戦相手を募集すると、アプリを閉じているあいだに申し込みが届いたことを
お知らせできます。このために、**端末ごとの通知用の識別子**
（Firebase Cloud Messaging のトークン）をサーバーへ保存します。

- 通知の許可は**募集を出すときにお尋ねします**。許可しなくても募集は
  できます（お知らせが届かないだけです）。端末の設定からいつでも
  変更できます
- お知らせの文面に**王国名やメッセージの内容は含めません**
  （「対戦の申し込みが来ています」の固定の文です）
- 通知用の識別子は、退会のときに削除します。また30日間更新のないものは
  自動的に削除します
- 広告・宣伝の目的では利用しません

### 5. 王国名（表示名）について

王国名は利用者が入力する表示名で、**対戦相手の画面と、ランキングに
表示されます。** ランキングには**王国名・国家戦力（レート）・チーム編成**が
載り、ログインしている他の利用者が見られます。
本名や連絡先など、他人に知られたくない情報は入力しないでください。

不適切な表示名への対策として、以下を行っています。

- 入力時のフィルタ（不適切な語を含む名前は登録できません）
- 対戦画面・結果画面からの**通報**（通報された内容と、通報された時点の
  双方の表示名を保存します）
- 通報した相手とは、以後ランダムマッチングされません
- 運営が不適切と判断した表示名は、予告なく既定の名前へ変更することがあります

通報に関する記録は、対応と再発防止のため保存します。通報された内容の写しは
対応の完了まで、以後マッチングしないための記録（双方の識別子のみ）は期限を定めず
保存します。

### 6. 広告について

本アプリは Google の広告配信サービス **Google AdMob** を利用しています。

AdMob は広告の配信・成果測定のために、広告識別子（IDFA / 広告 ID）や
おおまかな地域、端末の情報などを取得することがあります。これらは
Google によって取得・利用されるものであり、開発者がその内容を
参照することはできません。

Google によるデータの取り扱いについては、以下をご確認ください。

- [Google 広告に関するポリシー](https://policies.google.com/technologies/ads?hl=ja)
- [Google プライバシーポリシー](https://policies.google.com/privacy?hl=ja)

#### トラッキングの許可について（iOS）

iOS では、初回起動時にトラッキングの許可を求めるダイアログが表示されます。

- **許可しない場合**: 利用者に合わせた広告（パーソナライズ広告）は
  表示されなくなりますが、**ゲームの機能はすべて通常どおりご利用いただけます**。
- **許可した場合**: より関連性の高い広告が表示されます。

この設定は、iOS の「設定」アプリ →「プライバシーとセキュリティ」→
「トラッキング」からいつでも変更できます。

#### EU・英国・スイスにお住まいの方

該当地域では、初回起動時に広告に関する同意画面を表示します。
同意内容はホーム画面の「プライバシー設定」からいつでも変更できます。

### 7. お子さまの利用について

本アプリは特定の年齢層を対象として設計されたものではなく、
13歳未満のお子さまから意図的に個人情報を収集することはありません。

### 8. 本ポリシーの変更

本ポリシーは必要に応じて変更されることがあります。重要な変更がある場合は、
本ページの最終更新日を改めます。

### 9. お問い合わせ

本ポリシーに関するお問い合わせは、以下までご連絡ください。

minimumkingdom.info@gmail.com

---

## English

### 1. Introduction

This policy explains how information is handled in Minimum Kingdom
(the "App").

### 2. Information the developer collects

**The App never asks you to enter your name, phone number, address, or
similar personal information.**

**Once you finish the opening story and choose your kingdom name**, that
kingdom name and an anonymous identifier are stored on the developer's
servers (Google Firebase; see Section 4). Using online matches, friend
matches, or Diplomacy stores further information.

**Even before you finish the opening story, the App makes the following
connections.** None of them send the anonymous identifier described in
Section 4 or a kingdom name you have typed. However, as with any connection
over the internet, your IP address reaches the server you connect to. Google's
services (Firebase and AdMob) may also handle device-level identifiers of
their own (see Section 6).

- **Update check**: on every launch, the App asks the developer's server
  (Google Firebase) whether an update to the App is required. This is a
  read that does not identify you.
- **Ad setup**: on every launch, once the first screen has appeared, the App
  connects to Google's advertising service (AdMob) and starts loading ads.
  On your first launch, the iOS tracking permission dialog and, in the
  regions concerned, the consent screen are also shown at this point (see
  Section 6).
- **Kingdom-name availability**: when the kingdom-name screen opens, the App
  asks the developer's server whether the candidate names behind the
  「おまかせ」 (auto-suggest) button are already taken. Only the candidate
  names generated by the App are sent; **nothing you type is sent**.

**After you finish the opening story**, the App additionally checks at launch
that it can reach the server (the request carries no data and no identifier).

These connections are required for the App to work and cannot be turned off
individually. What the ads show can be changed as described in Section 6.

**Separately, once you have chosen a kingdom name, the App sends a coarse
count of how it is used** (see "Usage statistics" in Section 4). This is
sent whether or not you link an account.

### 3. Information stored on your device

The following is stored on your device and removed when you delete the
App.

- Number of wins against the CPU (per difficulty)
- Remaining deployment cost (stamina) and its recovery time
- Your team composition
- Your unit unlock progress
- Your kingdom name (display name) and whether initial setup is complete

**If you have linked an account, the four items above (all except the
initial-setup flag) are also stored on the server** so that they can be
restored (see "Account linking" in Section 4). Your kingdom name is
stored on the server whether or not you link an account (see Section 4).

### 4. Information stored on the server (kingdom name and matches)

**When you finish the opening story and choose your kingdom name**, or the
first time you use a match feature, an **anonymous identifier** (a random
string, not linked to your name or email) is created and stored on the
server together with:

- the anonymous identifier
- your **kingdom name (display name)**, which is shown to your opponent
  (see Section 5)
- your **coin balance and the dates you received the daily login bonus**
  (stored to prevent duplicate awards; entries older than 30 days are
  removed automatically)
- the **icons, frames, and units you have obtained** (used to detect
  duplicates and to show whether anything is left to draw)
- the **number of gacha draws you have made** (recorded for
  troubleshooting and statistics)
- your rating and match records (moves, results, timestamps; for ranked
  matches between players, also both players' kingdom names and teams)
- your connection status during a match

Match records are retained to detect cheating and to respond to inquiries.

#### Usage statistics

To learn which features are used and where players get stuck, the App sends
**coarse per-day counts** to the server. They are stored against your
anonymous identifier, and **only after you have chosen a kingdom name** and
that identifier exists.

Only the following counts are sent:

- how many times you opened the App
- how many CPU matches you started, won, and finished (by difficulty)
- how many passphrase matches you entered
- how many times you opened Exchange and how many messages you posted there
- how many times you opened the team screen
- how many times you could not play because your deployment cost (stamina)
  had run out
- how many ranked matches were made, finished, and ended early (with the
  reason)
- the App version that was running
- the time you were last recorded that day (used to tell repeat sends apart)

**The following are never included**: device identifiers, advertising
identifiers, device model, OS version, location, time spent on any screen,
which buttons you pressed, board actions, your kingdom name, or chat text.
**Nothing beyond the items listed above is sent.**

**These statistics are never used for advertising or promotion, and are
never shared with third parties.** There is **no separate setting to turn
them off** (they contain nothing beyond the items listed above).

Retention:

- **per-day counts are deleted automatically after 90 days**
- **monthly totals of people** (such as how many people were first recorded
  in a month, or played in it) are kept indefinitely — these are **counts
  only and are not linked to an individual**
- **the date you were first recorded, and flags for which features you have
  ever used**, are needed so that the same person is not counted twice, and
  are **kept until you delete your account**

Deleting your account (below) removes **all** of the per-day counts, the
first-recorded date, and the feature flags. Monthly totals of people remain,
as they are not linked to an individual.

#### Account linking (optional)

From "その他" → "アカウント設定" you may link an Apple or Google account so
that your data can be restored on a new device or reinstall.
**Linking is optional; all features work without it.**

If you link an account, the authentication service (Firebase
Authentication) stores the identifier and email address it receives from
Apple or Google. The on-device data listed in Section 3 (CPU win counts,
stamina, team composition, unit unlock progress) and the time you linked
are also stored on the server so that they can be restored. If you use
Apple's "Hide My Email", only the relay address is available to the
developer. Email addresses are never used for
advertising or promotion.

#### Account deletion

From "その他" → "アカウント設定" → "アカウントを削除" (Delete account) you can
delete your account and your data on the server. This also removes the parts
of the usage statistics above that are linked to you (the per-day counts, the
first-recorded date, and the feature flags). **Records of ranked (online)
matches are not deleted**, as they are used to detect cheating and to respond
to inquiries. They keep the identifiers of the players and the teams used,
with no time limit; for matches between players they also keep both players'
kingdom names shown during the match (they are also your opponents' records).
The record used to keep you from being matched with someone you reported
(both identifiers only) is also kept.
A record of **when you deleted your account** is also kept, to prevent your
balance from being recreated immediately after. For the full list of what is
deleted and kept, and how to request deletion if you cannot use the app, see
[Account & Data Deletion](./account-deletion.html).

#### Exchange (lobby chat)

"Exchange" is a shared space where players exchange short messages and
recruit opponents. When you use it, the following is stored on the server
and **shown to other players**:

- the message text, your kingdom name, your icon, the posting time, and
  your national power (rating)
- for a recruit post, the recruiting note and its state (open, closed)
- if you apply to a recruit post, your kingdom name and rating are shown
  **to the player who posted it**

Recruit posts and applications also store your **team composition**. It is
not shown in the lobby; it reaches your opponent when the match starts,
just as in an ordinary match.

Posts are **automatically deleted after 24 hours** (only the latest 100
are kept). A server-internal copy of each post's text is retained for up
to 7 days to handle reports (it is not shown to other players). If a
post is reported, a copy of its text is kept in the report record until
the report has been handled, after which it is deleted. Posts themselves
do not contain your identifier (uid); they contain a fixed anonymous
marker per poster instead. **The internal copy kept for handling reports
does contain the uid** (it is not shown to other players).

Safeguards for inappropriate posts: input filtering, long-press
reporting, hiding of posts from players you reported, and operator-side
deletion. You are asked to agree to the usage rules on first use.

#### Push notifications

When you recruit an opponent, we can notify you that someone applied
while the app is closed. For this purpose a **per-device notification
identifier** (a Firebase Cloud Messaging token) is stored on the server.

- Permission is requested **when you post a recruitment**. You can post
  without granting it (you simply will not be notified), and you can
  change it any time in your device settings
- The notification text contains **no kingdom name and no message
  content** (it is the fixed text "対戦の申し込みが来ています")
- The identifier is deleted when you delete your account, and any
  identifier not refreshed for 30 days is removed automatically
- It is never used for advertising or promotion.

### 5. Kingdom name (display name)

Your kingdom name is a display name you enter, and it **is shown to your
opponents and in the rankings.** The rankings show your **kingdom name,
rating, and team composition** to other signed-in players. Please do not
enter your real name, contact details, or any other information you do
not want others to see.

Safeguards for inappropriate display names:

- input filtering (names containing inappropriate words cannot be saved)
- **reporting** from the match and result screens (a report stores both
  players' display names at the time of the report)
- you are excluded from random matchmaking with someone you reported
- display names judged inappropriate may be reset to a default name
  without prior notice

Reports are retained to handle and prevent misuse: copies of the reported
content until the report has been handled, and the record used to keep the two
players from being matched again (both identifiers only) with no time limit.

### 6. Advertising

The App uses **Google AdMob** to display advertisements.

AdMob may collect an advertising identifier (IDFA / Advertising ID),
approximate location, and device information in order to deliver and
measure ads. This data is collected and used by Google; the developer
cannot access it.

For details on how Google handles this data, see:

- [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)
- [Google Privacy Policy](https://policies.google.com/privacy)

#### App Tracking Transparency (iOS)

On iOS, a tracking permission dialog is shown when you first launch the App.

- **If you decline**: personalized ads will not be shown, but **all game
  features remain fully available**.
- **If you allow**: you will see more relevant ads.

You can change this at any time in iOS Settings → Privacy & Security →
Tracking.

#### If you live in the EU, UK, or Switzerland

A consent screen for advertising is shown on first launch in these
regions. You can change your choices at any time from "プライバシー設定"
(Privacy settings) on the home screen.

### 7. Children

The App is not directed at any particular age group, and the developer
does not knowingly collect personal information from children under 13.

### 8. Changes to this policy

This policy may be updated as needed. If there are significant changes,
the "last updated" date above will be revised.

### 9. Contact

For questions about this policy, please contact:

minimumkingdom.info@gmail.com
