# web1-5

<!DOCTYPE html >
<html>
    <head>
        <meta charset="utf-8"/>
        <title>快適なゲーム環境</title>
    </head>
    <body>
    <h1>必要なもの</h1>
    <p>次のものを用意します</p>
    <ul>
    <li>お菓し</li>
    <li>ベッド</li>
    </ul>
    <table>
    <tr><th>物</th><th>分量</th><th>単位</th></tr>
    <tr><td>お菓子</td><td>適量</td><td>個</td></tr>
    <tr><td>ベッド</td><td>１</td><td>個</td></tr>
    <hl>分量</hl>
    <dl>
    <dt>お菓子</dt><dd>適量</dd>
    <dt>ベッド</dt><dd>1個</dd>
    </dl>
    <hl>手順</hl>
    <ol>
    <li>お菓子を開けます</li>
    <li>ベットに寝っ転がります.<br>そして好きな音楽を流します。</li>
    <li><strong>ゲームをします</strong></li>
    </ol>
    <p><audio src="music.mp3"controls>参考音楽</audio></p>
    <hl>アンケート</hl>
    <form  id="top"action="#"method="post">
    <p>テキストボックス<input type="text"name="input1"></p>
    <p><input type="submit"value="送信">
    　　<input type="reset"value="取り消し"></p>
      </form>
      <p>好きなゲームは
      <input type="radio"name="input11"value="dragonquest"checked>ドラゴンクエスト
      <input type="radio"name="input11"value="FF"checked>ファイナルファンタジー
      </p>
      <p>好きなゲームは
      <input type="checkbox"name="input11"value="dragonquest"checked>ドラゴンクエスト
      <input type="checkbox"name="input11"value="FF"checked>ファイナルファンタジー
      </p>
      <p>好きなゲームは
      <select name="input13">
      <option value="dragonquest">ドラゴンクエスト
      <option value="FF">ファイナルファンタジー
      </select>
      </p>
      <p>好きなゲームは
      <select name="input14"multiple>
      <option value="dragonquest"selected>ドラゴンクエスト
      <option value="FF"selected>ファイナルファンタジー
      </select>
      </p>
      
      
      </body>
    
</html>
