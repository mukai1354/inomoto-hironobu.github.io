<template>
	<main>
<p><abbr title="Cascading Style Sheet">CSS</abbr>とは<abbr title="Hyper Text Markup Language">HTML</abbr>に色や大きさなど、主に視覚的な情報を付加するための形式としてできたテキストです。主にウェブデザイナーが書くべきだと思うのでCSSを勉強してもらいたいと思います。<br/>
このファイルでは練習用の文章として「プロジェクト進行でのこれまでの雑感」章を用意しています。これらの中から基本となる構成要素のうち対象となる段落とキーワードをデザインしてみてください。.inline と .block でプロパティを書いて装飾を行ってください。<br/>
このファイルで埋め込みのCSSを設定していてその内容は下記にある通りです。参考にしてください。</p>
<pre id="display-sample"></pre>
<div class="block"></div>
<p>スタイルを設定できる箇所は「これまでの雑感」節にあるので、CSSを書いていくとどうなるのかを試していってみてください。</p>

<section>
<h2>プロジェクト進行でのこれまでの雑感</h2>
<p>プロジェクトを進行していく中で考えた事や感じた事を書いてみます。</p>
<section>
<h3>作業の優先順位と割り振り</h3>
<p class="block">どのプロジェクトか明瞭ではない場合、例えばウェブ案件に関して何かをしてほしい、というような範囲の広いものを依頼された場合は確認が必要になります。
いくつかが当てはまるなら、場合分けで指示を出すこともできますが、それぞれの事にどうすればいいか考えなければならないので、労力の無駄が生じると言えます。<br/>
また、作業の成果に対して評価し改めて作業の割り振りを考えた方がいいかもしれません。作業依頼はその人にしかできない作業を割り振り誰でも出来そうなものは振らないようにした方がいいでしょう。<br/>
仕事の依頼作業を変更する場合は変更理由や作業の必要性、作業を担える能力があるとは限らないのでその確認などをする必要があり、その連絡手段ができる良い環境を用意しておくべきだと思います。<br/>
作業が割り振られていない事を言われた場合は、どうすべきかは必ずしも定かではないと思いますが、私の場合は練習もかねて他の利用者も使えるような下地となる画像を作ってみてはどうかと提案しました。</p>

<h3>報連相や情報共有の手段</h3>
<p class="in-style-block">連絡手段については口頭、Gmail、Googleドライブなどを使ったが、私の場合は一応全て目を通してから要らないと判断したものは削除するようにしていますが、サイボウズからの新着情報などは特に目を通す必要はないと思いますので、未読で削除しても構わないでしょう。</p>

<h3>近況を公開的に報告する意義</h3>
<p class="block">Googleドライブを社内で使うことになった時、それについて知っている人がいない状態でした。そのため、個々各々で調べていたと思いますが、それぞれやっていたことは違っていたでしょうけれど、一方で同じことを調べたり試していたりしていた場合、簡単に分かるものならともかく、時間のかかるものならそれぞれが労力を消費しますが、近況を書いておけば一人が労力を消費するだけで済むからです。

パソコンの事なんでもという<span class="inline">テーマチャット</span>で何か困ったことで、多くの人に知ってもらいたいことがあれば、ここに書いてもらえますか？
社内で見れるようになっているので助けになると思います。<br/>
いづれも無理に使う必要はないですが、他の利用者も助けになると思います。

</p>

<h3>プロジェクトのファイルとフォルダの管理</h3>
<p class="in-style-block">世にファイルの共有の仕方は色々ありますが、いずれにせよファイルの置き場所の整頓をすることは重要だと思います。現在では<span class="inline">Googleドライブ</span>を使っています。</p>
</section>
<!-- /h3 -->
<ul class="references">
<li><a href="https://cybozulive.com/mpAddress/top">近況を書く</a></li>
<li></li>
<li></li>
</ul>
</section>
<!-- /h2 -->
<pre id="display-sample"></pre>

<div class="section">



<h2 style="clear: both">サンプル</h2>
<div class="">
<div class="view">

</div>
<fieldset id="sample-controll" class="controll">
<label>コントロール</label>
<table>
<tr><td>繰り返し数</td><td><input id="num" value="" type="text" size="4"></input></td></tr>
<tr><td>x</td><td></td></tr>
<tr><td colspan="2"><button type="button" onclick="sampleScript()" value="invoke">test</button></td></tr>
<tr><td>y</td><td></td></tr>
</table>
</fieldset>
</div>
<hr style="clear: both"/>
</div>
</main>
</template>
<script>
	window.addEventListener("load",function() {
	displaySample();
});
</script>