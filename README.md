# プログラマー向け成果物セルフチェックリスト

プログラマー向け成果物セルフチェックリスト（以下、本チェックリスト）は、Javaを使ったシステム開発において、コーディング規約違反などの単純なコーディングミスをしていないかを開発者自身が確認するためのチェックリストです。なお、公開している本ドキュメントはサンプルとして[Nablarch](https://nablarch.github.io/docs/LATEST/doc/)をフレームワークに採用した場合の記載としています。

大規模なシステム開発では、様々なスキルや経験を持った多くの開発者が参画するため、開発者が有するスキルや経験の差による品質のばらつきが多くなる傾向があります。
スキルや経験が不十分な開発者の成果物は、レビュー時に本質的でないレビュー指摘が増えることでレビューアの負荷が増大し、本質的なレビュー指摘に注力できないことで品質低下につながるリスクがあります。

そこで、本チェックリストは、開発者自身で事前にチェック・修正することで、レビュー前の品質向上およびレビューアの負荷軽減により、品質低下を防止する役目を担います。

なお、Nablarchの使用を前提にしていますが、Nablarchに依存するチェック項目は約３割です。残りの７割はJava、SQL、テスト、UIについて注意すべきポイントをチェック項目としています。Nablarch以外のフレームワークを使用する場合は、PJの状況に合わせてカスタマイズすることで適用可能なものになっています。

## 使用方法

- 本チェックリストをPJに適用する前に、チェック項目を確認し、PJの状況に合わせてカスタマイズしてください。なお、静的チェックツールにてチェック可能な項目は、ツールによるチェックを本チェックリストのチェックとは別で実施している前提のため、チェック項目には記載していません。

    ＜カスタマイズ例＞

    　　（例１）PJで定義しているコーディング規約と異なる部分があったため、該当する項目をカスタマイズした。

    　　（例２）PJで利用している静的チェックツールで代替できるチェック項目があったため、該当する項目はチェック対象外とした。

    　　（例３）Nablarch以外のフレームワークを利用した案件のため、Nablarchに依存する項目のみをカスタマイズして利用した。

    　　（例４）開発者のJavaスキルレベルが高く、開発標準やコーディング規約も事前に共有できているが、Nablarchの利用経験が少ないメンバが多い案件では、Nablarchに依存する項目のみをチェック対象とした。

- 開発者のスキルや経験と開発プロセスを考慮した上で、本チェックリストの運用方法を定義し、PJ内で共有した上で運用してください。チェックリストの運用方法を検討する際に、過剰なチェックを開発者に課すことで、チェック行為そのものが形骸化しないように注意してください。

      ＜チェックリストの運用例＞
      
      　　（例１）レビュー依頼する前には、必ず本チェックリストによるセルフチェックを実施する運用とした。（３割時点でレビュー依頼する場合も含む）
      
      　　（例２）チェック項目をコーディング完了時と単体テスト完了時に分けて、それぞれのタイミングで確認する運用とした。
      
      　　（例３）全員が全てのチェックを実施する必要が無いと考えて、レビューアが十分なスキルをもった開発者と判断した開発者は、チェックを免除した。

## 関連文書

- [PG・UT作業の完了条件チェックリスト](https://fintan.jp/?p=1367)

  　本チェックリストにてチェックすることを、PG・UT作業の完了条件チェックリストのチェック項目とすることで、PG・UT作業に漏れが無いようにしています。

- 各種コーディング規約

  　[Javaコーディング規約](https://github.com/nablarch-development-standards/nablarch-style-guide/blob/master/java/java-style-guide.md)などの各種コーディング規約から、特に注意する必要がある項目を本チェックリストに項目を定義することで、効率良く開発を進められるようにしています。

## 入手方法

こちらから参照、ダウンロードしてください。

- [プログラマー向け成果物セルフチェックリスト.xlsx](./docs/プログラマー向け成果物セルフチェックリスト.xlsx?raw=true)

## ライセンス

この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">クリエイティブ・コモンズ 表示 - 継承 4.0 国際 ライセンス</a>の下に提供されています。
<br />
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
  <img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
</a>