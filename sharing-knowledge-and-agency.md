# 専門知識を共有し、現場の主体性を支える開発

この文書は、林業に関わるツールを開発する私自身の哲学を記すものです。
開発者と、そのツールを使う現場の人の両方に向けています。
特定の開発者への批判や、業界全体についての調査結果ではありません。

## 専門性と、その内側で完結する構造

専門知識は、現場を支える大切な力です。一方で、専門性の高い開発では、
所属する分野の知識、目的、言葉、慣習を当然の前提として設計しやすくなります。
その範囲では十分に通じるため、外部の人に何が伝わっていないかに気づきにくい。
排除する意図がなくても、結果として理解や参加への壁が生まれます。

私が緩めていきたいのは、この構造の強固さです。
専門性を持つ人が、その知識を開発に注ぐのであれば、その知識を他の人も
理解し、確かめ、使える形で渡すことを、開発の一部として大切にしたいと考えています。

## 機能の公開と、知識の共有

FOSSとしてコードを公開することには意味があります。
ただし、コードを読めることと、その処理の意味や判断の根拠を理解できることは別です。
私にとってFOSSの開発は、機能とともに、それを使うための専門知識も共有する実践です。

なぜその手法を選ぶのか。どの条件で使えるのか。設定を変えると何が変わるのか。
結果から何を判断でき、何を判断できないのか。そして、その先にどんな仕事があるのか。
こうした知識を、専門教育や専門家との接点を持つ人だけが享受する状態を緩めたいのです。

日本語で使えるようにすることにも、英語のツールで手法の理解を助けることにも価値があります。
計算が既存機能と同じでも、利用者の理解や判断の力を育てるなら意味があります。
私が重視するのは、新規性だけでなく、誰が何をできるようになるかです。

## 処理がつながることと、仕事につながること

入力、解析、出力を統合すれば、操作は便利になります。
しかし、GeoTIFFや地図を作れることだけでは、それを使って人が何をするかは説明できません。
出力形式までの流れと、現場の仕事までのつながりは、それぞれ考える必要があります。

AIによって解析の実装や実行が容易になるほど、計算や出力を提供することだけで
価値を示すのは難しくなると私は考えています。
そのとき、何を調べるべきか、結果をどう読み、どこに限界があり、次にどう行動するかを
利用者が考えられるようにする設計が、より重要になります。

複雑なプラグインにHTMLマニュアルを同梱するのも、そのためです。
操作手順に加え、目的、前提、設定の意味、結果の読み方、実務での使い方を伝えたい。
それは内部の人だけに通じる説明で終わっていないかを、私自身も問い続ける必要があります。

## 現場を、情報の提供者だけにしない

林業のツールは、林家と、林業の現場で働く人たちを軸に考えたい。
何を課題とし、どう評価し、成果をどう使うかを決める過程に、その人たちの知識と判断が必要です。

現場から情報や経験を集めても、解釈する力や成果の利用機会が専門家側に集中し、
現場に依存だけが残るなら、一方向の関係になります。
情報の提供と引き換えに、現場の知識や資産の価値が外へ移り、現場に十分な力が返らない。
開発は、そのような収奪の構造を持ち得ます。FOSSという形式だけでは防げません。

現場から得た知識を、現場自身が理解し、検証し、選択できる力として返していく。
私は、それを開発の方向を確かめる基準にしたいと考えています。

## ツールを使う現場の人へ

専門教育を受けていないことだけを理由に、疑問を控える必要はありません。
「この結果は自分の仕事にどう関係するのか」「なぜこの条件なのか」
「現場の状況と合わないのはなぜか」と問うことは、ツールを良くするためにも大切です。

現場の経験は、解析へ投入する情報であると同時に、解析の前提や結果を問い直す知識でもあります。
専門家と現場が互いの知識を確かめ、結果を採用するか、追加確認するか、使わないかを
話し合える関係を作りたい。その関係を支えることも、私がツールを開発する目的です。

---

# Sharing Knowledge and Supporting Agency in Field Work

This is a statement of my own philosophy as a developer of forestry tools.
It is addressed both to developers and to people who use these tools in their work.
It is not a criticism of a particular developer or a survey of an entire industry.

## Expertise and the Boundaries It Can Create

Expertise is valuable. Yet developers with specialized knowledge can take their
field's language, purposes, and conventions for granted. A design may make sense
within that field while leaving people outside it without a way to understand
or participate. This can happen without any intention to exclude them.

I want to loosen these boundaries. When developers put specialist knowledge
into a tool, helping others understand, examine, and use that knowledge should
be part of the development itself.

## Publishing Functions and Sharing Knowledge

Publishing source code as FOSS matters. Access to code, however, does not by
itself explain the reasoning behind a method or a decision. For me, FOSS
development also means sharing the specialist knowledge needed to use a tool.

Why choose this method? Under what conditions does it apply? What changes when
a setting changes? What can the result support, and what can it not support?
What work comes next? Access to this understanding should extend beyond people
with specialist education or connections to experts.

A Japanese interface can lower barriers. An English tool can also help people
learn how a method works. Even when the calculation already exists elsewhere,
helping users understand and make decisions can be valuable. I care about who
becomes able to do what, as well as whether a function is new.

## Connecting Processing and Connecting Work

Combining input, analysis, and export can make operations easier. Producing a
GeoTIFF or a map still leaves the question of what someone will do with it.
A processing sequence and a connection to practical work each need attention.

As AI makes analysis easier to implement and run, I expect calculations and
outputs alone to become less distinctive. Design should help people consider
what to investigate, how to interpret results, where the limits are, and what
action to take next.

This is why I tend to include HTML manuals with complex plugins. Alongside
operating instructions, I want to explain purposes, assumptions, settings,
interpretation, and practical uses. I also need to keep asking whether these
explanations make sense to people outside my own circle.

## Field Practitioners as Participants in Decisions

Forestry tools should be built around forest owners and the people working
in forestry. Their knowledge and
judgment belong in deciding what problems matter, how to assess results, and
how those results will be used.

If information and experience flow from the field to specialists while the
ability to interpret and benefit from them stays with specialists, the
relationship becomes one-sided. The value of local knowledge and assets can
move outward while practitioners receive little ability to act independently.
Development can reproduce this extractive structure. A FOSS license alone
does not prevent it.

I want knowledge gained from the field to return as a greater ability for
practitioners to understand, verify, and choose. That is a standard by which
I want to judge the direction of my own development.

## To the People Using These Tools

Lacking specialist education is no reason to hold back a question. Asking how
a result relates to your work, why a condition was chosen, or why an output
does not match what you see in the field helps improve the tool.

Field experience is both information for analysis and knowledge that can
challenge its assumptions and results. I want experts and practitioners to
examine each other's knowledge and discuss whether to use a result, check it
further, or set it aside. Supporting that relationship is part of why I build
these tools.
