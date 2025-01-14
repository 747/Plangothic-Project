![Image text](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic/blob/main/pic/31.png)

[中国語/中文](README.md) | [英語/English](README.en.md)

# Plangothic Project

## 概要
Plangothic Project（プランゴシックプロジェクト、中国語：遍黑体项目）は、[源ノ角ゴシック](https://github.com/adobe-fonts/source-han-sans)の中国大陸部分に基づいて、CJK統合拡張ブロックを補完するゴシック体フォントの作成を目指すプロジェクトです。このプロジェクトは2020年6月頃にスタートします。

## 収録範囲

当フォントは今CJK統合漢字拡張Bを除いてすべて完成したが、拡張C·D·E·Fはまだ推敲されておらず。他の非CJK統合漢字ブロック部分が使用できます。

## 主な貢献者
- 主制作：[Fitzgerald](https://github.com/Fitzgerald-Porthmouth-Koenigsegg)、[Usagixineist](https://github.com/Usagixineist)、[La Striverage](https://github.com/Lastriverage)
- 共同制作：[Siphercase](https://github.com/Siphercase)、[KathrynCG](https://github.com/KathrynCG)、[Hulenkius](https://github.com/Hulenkius)、[Xiuer](https://github.com/Steve-Yuu)
- 技術協力：[0xAA55](https://github.com/0xAA55)、[Henry Chan](https://github.com/hfhchan)、[Baysoftware](https://github.com/yi-bai)、Eiso Chan、[SomeyaMako](https://github.com/SomeyaMako)

また、他にご協力を頂いた関係各位の方々も、心より感謝を申し上げます。

## ライセンス
当フォントは源ノ角ゴシックから派生したものので、SIL Open Font Licenseのもとで公開されています。詳しい説明は[ライセンスファイル](LICENSE.txt)をご覧ください。次のことができます：

- 無料で利用できます。商用を含めて、無料で、原作者に知らせたり、明記したりする必要はありません。
- フォントファイルを自由に共有し、任意のソフトウェアデバイスにインストールします。
- その上で修正または二次創作を行うが、二次修正された作品は「Plangothic」「遍黑」という名称を再使用することは厳禁であり、二次修正されたバージョンもSIL Open Font Licenseで発表する必要がある。

ただし、個人、企業、チームなどが本フォントを使用、複製、修正、配布したり、本フォントに対してSIL Open Font Licenseの規定に合致する行為を行ったりしている場合、契約規定の権利を使用、ダウンロード、または行使する受諾者、すなわちデフォルトではSIL Open Font Licenseのすべての規定を遵守することに同意したものとみなされます。

個人も法人も当プロジェクトのフォントファイルを販売すること（フォントファイル単体での販売、他のフォントとのバンドル販売、フォントの使用に対する対価の要求等を含むが、これに限らない）は固く禁じられています。もし、このフォントの代金を支払った場合は、直ちに報告し、必要に応じて関連する司法当局に協力してください。

## よくある質問
**Q1**：なぜPlangothicのフォントファイルは2つあるのですか？

**A1**：1フォントファイルで収容可能な最大グリフ数は65535に制限されていますが、CJK漢字の数はこの数値よりずっと大きいからです。

**Q2**：P1のfallback版とallideo版の違いは何ですか？

**A2**：fallback版では、まだ制作していないCJK漢字が空白になりますので、他に全部のCJK漢字を含むフォールバックフォントをインストールしていない方々はご利用する際には文字が表示できない場合があります。allideo版は、2つのフォントをインストールした上、全部のCJK漢字を表示したいユーザー向けのバージョンで、まだ制作していないCJK漢字は花園明朝（HanaMin）に置き換えられています。どちらのフォントファイルも、Plangothic現在の進捗状況を了解することができます。

**Q3**：なぜP1だけが2種類に分かれているのですか？

**A3**：P2の対象である拡張Gと拡張HのCJK漢字は全て制作済みなので、P2を分ける必要がないからです。

**Q4**：なぜこのプロジェクトにはUROと拡張Aの漢字が含まれていない（または少量含まれている）のですか？

**A4**：本プロジェクトの趣旨は「[源ノ角ゴシック](https://github.com/adobe-fonts/source-han-sans)による補足」であるため、UROと拡張AのCJK漢字を表示する必要がある場合は、そのまま源ノ角ゴシックを使用すればよく、本プロジェクトに含まれる零細なUROと拡張AのCJK漢字は、いずれもUnicode内にグリフ変更があったり、本プロジェクトの趣旨に合わないCJK漢字であり、これらのCJK漢字を追加する前に、いずれも他の主流フォントとUnicode内のグリフと比較されています。

**Q5**：将来、他のウェイト（または他のローカルグリフ）を含むバージョンがありますか？

**A5**：このプロジェクトの工事量が多すぎるので、この計画はありません。このような考えがある場合は、必要に応じてプロジェクトの派生フォントバージョンを作成できます。

**Q6**: なぜこのフォントに複雑なテキストレイアウト（CTL）がないのでしょうか？

**A6**: このプロジェクトでのフォントの使用はツールフォントに集中しているため、つまり、[綿雲飴里](https://github.com/MY1L)が開発した[Noto Unicode](https://github.com/MY1L/Unicode/tree/main/NotoUnicode)のようなものです，または[Unifont](https://unifoundry.com/unifont)です。文字が見えさえすれば、そんなに多くの言語や文字を正確にレイアウトする必要はありません。このような考えがある場合は、必要に応じてプロジェクトの派生フォントバージョンを作成することができます。

## ご寄付のお願い
「蹞歩を積まざれば、以って千里に至るなし。」非常に困難で時間のかかるプロジェクトですので、もしご支援いただけたら、心から感謝いたします。皆様からのご寄付は、当プロジェクトのより良い発展に重要な役割を果たします。また、間違ったグリフのチェックや、下手なグリフの改善提案など、様々な形で貢献することも可能です。

寄付をする前に、ぜひ以下の点にご注意ください。

- 寄付をする前に、アカウント名をよく確認してください（Alipay：Fitzgerald K.、WeChat：蔽芪茢·茇䓮·蓲䒤菥。ユーザー名が変更したらすぐに訂正します）。不正行為により被る損害について、当プロジェクトは一切の責任を負いません。
- 現在、公式の寄付ページはこれだけです。他のサイトで当プロジェクトへの寄付リンクを見かけた場合は、直ちに報告し、必要に応じて関連する司法当局に協力してください。
- 当プロジェクトにご寄付いただくことは、私たちの理念に賛同し、このような形で私たちの発展を支援することを黙認していることになります。寄付者様からのご意見は慎重に検討させていただきますが、いくら寄付をいただいても、寄付者が個人の意思で当プロジェクトの目的や公益性を変更する権利はありません。
- ご希望の方には、当プロジェクトにご協力いただいたお礼として、ご寄付いただいた時間と金額を明記してメッセージを残すことができます。
- 寄付金は全て個別に記録され、当プロジェクトの技術支援などに使用され、個人的な使用はされません。
- 上記の寄付方法は、中国大陸部のユーザーにのみ適用され、中国大陸部のユーザーではない場合は、[本リンク](https://paypal.me/fitzgeraldpk?country.x=C2&locale.x=zh_XC)を通じて直接寄付すればよい。寄付をする前に、アカウント名をよく確認してください（ユーザー名：@fitzgeraldpk、名前：于航。ユーザー名が変更したらすぐに訂正します）。不正行為により被る損害について、当プロジェクトは一切の責任を負いません。
![Image text](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic/blob/main/pic/1650383987393.jpg)

## 連絡先
- GitHub：https://github.com/Fitzgerald-Porthmouth-Koenigsegg
- ツイッター：https://twitter.com/Fitzgerald_P_K_/
- グリフウィキ：http://zhs.glyphwiki.org/wiki/User:fitzgerald
- メール：374601620@qq.com、fitzgeraldkoenigsegg@gmail.com
- QQ: 374601620

## その他の説明
1. Plangothicの制作には、誰でも参加することができます。しかし、地域の字形、字形の美しさ、ソフトウェアの使用、Unicodeなどの面で一定の基礎があることを確認し、この点については、QQグループ[1135661191](https://jq.qq.com/?_wv=1027&k=xRTzFAfD)に参加することで、このプロジェクトについて検討したり、質問したりすることができます。
2. 当プロジェクトは長期的ですので、他の人に宣伝していただけるとありがたいです。また、私たちもフォント制作の技術者を歓迎して、みんなが本フォントの基礎の上で引き続きこのフォントを改善することを歓迎して、あなたは上記の連絡先を通じて作者と連絡することができます，このプロジェクトの発展はあなた达の宣伝と励みを离れない。
3. 本人はプロのデザイナーではなく、構造が醜いかもしれませんが、補足された字は原版と比べて違和感があるかもしれません。また、時間が迫っているため、修理する余裕がなく、一部の字の部品の接合がぎこちなくなることがあります。しかし、ないよりはましだ。
4. **私は中国本土のユーザーで、このプロジェクトにはTelegram、Discordなどの海外ディスカッショングループはありません。海外ユーザーのご迷惑をおかけして申し訳ありません！**
5. 本プロジェクトは、主に次のような他のツールまたはオープンソースフォントプロジェクトの一部またはすべてを借用または参照しています：
    - [源ノ角ゴシック](https://github.com/adobe-fonts/source-han-sans)。
    - Notoシリーズの他のフォント。
    - [上地宏一](https://twitter.com/kamichikoichi)が開発した[グリフウィキ](https://glyphwiki.org/wiki/GlyphWiki:%e3%83%a1%e3%82%a4%e3%83%b3%e3%83%9a%e3%83%bc%e3%82%b8)とKAGE Engine。
    - [すきまゴシック](https://oppekebekkanko.booth.pm/items/2117070)。
    - [綿雲飴里](https://github.com/MY1L)が開発した[Noto Unicode](https://github.com/MY1L/Unicode/tree/main/NotoUnicode)。
    - [Chiron Hei HK（昭源黑體）](https://github.com/chiron-fonts/chiron-hei-hk)。
    - [奈白不弍](https://github.com/Buernia)が開発した[Zhudou-Sans（煮豆黑體）](https://github.com/Buernia/Zhudou-Sans)。
    - [ChiuKong Gothic（秋空ゴシック）](https://github.com/ChiuMing-Neko/ChiuKongGothic)。
    - [Nôm Na Tống](https://github.com/nomfoundation/font)。
    - [魏安（アンドリュー・ウェスト）](https://twitter.com/BabelStone)が開発した[BabelStone Han](https://www.babelstone.co.uk/Fonts/index.html)。
    - [白易](https://github.com/yi-bai)が開発した[Zitools](https://zi.tools)。
