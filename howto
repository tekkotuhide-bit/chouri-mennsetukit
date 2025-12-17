<!doctype html>
<html lang="ja">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>調理職員 来園対応 台本（当日用）</title>
  <style>
    :root{
      --bg:#0b1220; --card:#0f1a33; --line:rgba(255,255,255,.12);
      --text:rgba(255,255,255,.92); --muted:rgba(255,255,255,.70);
      --accent:#76a9ff; --ok:#7CFFB2; --warn:#FFD37C;
    }
    *{box-sizing:border-box}
    body{
      margin:0; padding:22px;
      font-family: system-ui, -apple-system, "Segoe UI","Hiragino Sans","Noto Sans JP","Yu Gothic", sans-serif;
      background: radial-gradient(1200px 600px at 20% 0%, rgba(118,169,255,.18), transparent 60%),
                  radial-gradient(900px 500px at 90% 20%, rgba(124,255,178,.12), transparent 55%),
                  var(--bg);
      color:var(--text);
    }
    .wrap{max-width:980px; margin:0 auto}
    .top{
      display:flex; gap:12px; flex-wrap:wrap; align-items:stretch;
      margin-bottom:14px;
    }
    .title{
      flex:1 1 460px;
      background:linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.02));
      border:1px solid var(--line);
      border-radius:16px;
      padding:14px 16px 12px;
    }
    h1{font-size:18px; margin:0 0 6px}
    .sub{font-size:13px; color:var(--muted); line-height:1.55}
    .mini{
      flex:0 1 340px;
      background:rgba(255,255,255,.03);
      border:1px solid var(--line);
      border-radius:16px;
      padding:12px;
      display:flex; flex-direction:column; gap:10px;
      min-width:290px;
    }
    .row{display:flex; gap:10px; align-items:center; flex-wrap:wrap}
    .label{font-size:12px; color:var(--muted); min-width:70px}
    .field{
      flex:1;
      padding:8px 10px;
      border-radius:12px;
      border:1px dashed rgba(255,255,255,.20);
      background:rgba(0,0,0,.12);
      color:var(--text);
      min-height:34px;
    }
    .field[contenteditable="true"]:focus{
      outline:2px solid rgba(118,169,255,.55);
      border-color:transparent;
      background:rgba(118,169,255,.10);
    }
    .btns{display:flex; gap:8px; flex-wrap:wrap}
    button{
      appearance:none; border:1px solid var(--line);
      background:rgba(255,255,255,.06);
      color:var(--text);
      border-radius:12px;
      padding:8px 10px;
      cursor:pointer;
      font-size:12px;
    }
    button:hover{background:rgba(255,255,255,.10)}
    .grid{
      display:grid;
      grid-template-columns: 1fr;
      gap:12px;
    }
    .scene{
      background:rgba(255,255,255,.03);
      border:1px solid var(--line);
      border-radius:16px;
      padding:14px;
    }
    .sceneHead{
      display:flex; gap:10px; justify-content:space-between; align-items:flex-start;
      margin-bottom:10px;
    }
    .sceneTitle{font-size:14px; margin:0}
    .pill{
      font-size:11px; padding:4px 8px; border-radius:999px;
      border:1px solid var(--line);
      color:var(--muted); white-space:nowrap;
    }
    .block{
      border:1px solid rgba(255,255,255,.10);
      background:rgba(0,0,0,.10);
      border-radius:14px;
      padding:10px;
      margin-bottom:10px;
    }
    .bTitle{
      font-size:12px; color:var(--muted);
      display:flex; align-items:center; justify-content:space-between;
      margin-bottom:6px;
    }
    .check{
      display:flex; gap:8px; align-items:center;
      font-size:12px; color:var(--muted);
    }
    .check input{transform:scale(1.15)}
    .lines{display:flex; flex-direction:column; gap:8px}
    .line{
      display:flex; gap:10px; align-items:flex-start;
      padding:8px 10px;
      border-radius:12px;
      border:1px solid rgba(255,255,255,.08);
      background:rgba(255,255,255,.03);
    }
    .tag{
      font-size:11px;
      padding:3px 8px;
      border-radius:999px;
      border:1px solid rgba(255,255,255,.14);
      color:var(--muted);
      white-space:nowrap;
      height:fit-content;
      margin-top:2px;
    }
    .say{font-size:13px; line-height:1.6}
    .note{font-size:12px; color:var(--muted); line-height:1.6; margin-top:4px}
    .memo{
      border-radius:14px;
      border:1px dashed rgba(255,255,255,.18);
      background:rgba(0,0,0,.12);
      padding:10px;
      min-height:72px;
      font-size:13px;
      line-height:1.6;
      color:var(--text);
    }
    .memo:focus{outline:2px solid rgba(118,169,255,.55); border-color:transparent}
    .k{color:var(--ok); font-weight:700}
    .w{color:var(--warn); font-weight:700}
    .footer{margin-top:12px; font-size:12px; color:var(--muted); line-height:1.6}

    @media print{
      body{background:#fff; color:#111; padding:0}
      .wrap{max-width:none}
      .title,.mini,.scene,.block,.line,.memo{background:#fff; color:#111}
      .title,.mini,.scene{border:1px solid #ddd}
      .block,.line{border:1px solid #e6e6e6}
      .pill,.tag{border:1px solid #ddd; color:#555}
      .sub,.label,.note,.footer,.bTitle{color:#444}
      .memo{border:1px dashed #bbb}
      button{display:none !important}
      .scene{break-inside:avoid}
      .block{break-inside:avoid}
      .line{break-inside:avoid}
    }
  </style>
</head>

<body>
<div class="wrap">

  <div class="top">
    <div class="title">
      <h1>調理職員 来園対応「台本」｜当日読むだけ進行</h1>
      <div class="sub">
        使い方：<b>上から順に読む → セリフを言う → チェック</b>。<br/>
        目的：<span class="k">安心感</span>＋<span class="k">聞き漏れゼロ</span>＋<span class="k">条件の曖昧さゼロ</span>。
      </div>
    </div>

    <div class="mini">
      <div class="row"><div class="label">日付</div><div class="field" contenteditable="true" id="dateField">2025年12月17日（水）</div></div>
      <div class="row"><div class="label">来園者</div><div class="field" contenteditable="true" id="nameField">（氏名）</div></div>
      <div class="row"><div class="label">担当</div><div class="field" contenteditable="true" id="ownerField">園長：三浦 ／ 同席：＿＿＿＿</div></div>
      <div class="btns">
        <button onclick="setToday()">今日の日付</button>
        <button onclick="window.print()">印刷（A4）</button>
      </div>
    </div>
  </div>

  <div class="grid">

    <!-- SCENE 0 -->
    <section class="scene">
      <div class="sceneHead">
        <h2 class="sceneTitle">Scene 0｜直前準備（来園前）</h2>
        <span class="pill">3分</span>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>行動</span>
          <label class="check"><input type="checkbox">準備完了</label>
        </div>
        <div class="lines">
          <div class="line">
            <div class="tag">行動</div>
            <div>
              <div class="say">面接場所を整える（椅子／資料／筆記具／水）</div>
              <div class="note">※「待たせない」「迷わせない」が勝ち。</div>
            </div>
          </div>
          <div class="line">
            <div class="tag">行動</div>
            <div>
              <div class="say">厨房見学をするなら、導線を決めておく（入口→動線→保管→洗浄）</div>
              <div class="note">※現場を止めない。質問は最後にまとめてもらう。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="bTitle">メモ（園側の確認）</div>
      <div class="memo" contenteditable="true" id="preMemo">例）面接後に共有する相手：厨房責任者／事務／配置担当（必要最小限）</div>
    </section>

    <!-- SCENE 1 -->
    <section class="scene">
      <div class="sceneHead">
        <h2 class="sceneTitle">Scene 1｜来園〜受付（最初の30秒）</h2>
        <span class="pill">2分</span>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>言う（そのまま）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「本日はお越しいただきありがとうございます。しもごおり山の手保育園、園長の三浦です。こちらへどうぞ。」</div>
              <div class="note">※名乗り＋誘導で、相手の緊張が一段落ちる。</div>
            </div>
          </div>
          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「感染対策で、こちらで手指消毒だけお願いします。園内は撮影はご遠慮いただいています。」</div>
              <div class="note">※長く言わない。淡々と。</div>
            </div>
          </div>
          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「今日は、面接が30〜40分ほどで、そのあと可能なら厨房を5分ほどご案内します。大丈夫ですか？」</div>
              <div class="note">※流れ提示＝安心。ここで承諾を取る。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="bTitle">メモ（第一印象・受付）</div>
      <div class="memo" contenteditable="true" id="arrivalMemo">例）挨拶／清潔感／受け答え／遅刻の有無／体調 など</div>
    </section>

    <!-- SCENE 2 -->
    <section class="scene">
      <div class="sceneHead">
        <h2 class="sceneTitle">Scene 2｜導入（緊張をほぐして本題へ）</h2>
        <span class="pill">3分</span>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>言う（そのまま）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>
        <div class="lines">
          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「まずは今日はお時間ありがとうございます。緊張されると思うので、雑談は短めにして、確認したいことを順に伺いますね。」</div>
              <div class="note">※“短めにします宣言”が、逆に安心感になる。</div>
            </div>
          </div>
          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「こちらも選ぶだけではなく、お互いに合うかを確認する場にしたいです。気になることは遠慮なく言ってください。」</div>
              <div class="note">※“対等さ”で応募者体験が良くなる。</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- SCENE 3 -->
    <section class="scene">
      <div class="sceneHead">
        <h2 class="sceneTitle">Scene 3｜経験確認（調理職員としての核）</h2>
        <span class="pill">12〜15分</span>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>聞く → 深掘り（そのまま読める）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">質問</div>
            <div>
              <div class="say">「まず、今までの調理のご経験を、どんな現場で・何人分くらいか、ざっくり教えてください。」</div>
              <div class="note">深掘り：「大量調理」「食数」「一日の流れ」「一人作業かチームか」</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">質問</div>
            <div>
              <div class="say">「一番大変だった日の話、覚えてますか？ その時どう段取りしました？」</div>
              <div class="note"><span class="w">見るポイント</span>：パニック耐性／優先順位／報連相／安全意識</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">質問</div>
            <div>
              <div class="say">「衛生面で“これは絶対崩さない”っていう自分ルールはありますか？」</div>
              <div class="note">例：温度管理／交差汚染／手洗いタイミング／記録の取り方</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">質問</div>
            <div>
              <div class="say">「アレルギー対応や、食形態（刻み等）を扱った経験はありますか？」</div>
              <div class="note">深掘り：「誤配防止」「声かけ」「表示」「確認のクセ」</div>
            </div>
          </div>

        </div>
      </div>

      <div class="bTitle">メモ（経験・具体エピソード）</div>
      <div class="memo" contenteditable="true" id="expMemo"></div>
    </section>

    <!-- SCENE 4 -->
    <section class="scene">
      <div class="sceneHead">
        <h2 class="sceneTitle">Scene 4｜価値観（園に合うかの確認）</h2>
        <span class="pill">8〜10分</span>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>聞く（そのまま）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">質問</div>
            <div>
              <div class="say">「調理の仕事で、大切にしていることを一言で言うと何ですか？」</div>
              <div class="note">深掘り：「その理由」「その考えになった経験」</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">質問</div>
            <div>
              <div class="say">「逆に、苦手なこと・不安なことがあれば、先に教えてください。」</div>
              <div class="note"><span class="w">見るポイント</span>：自己理解／正直さ／改善姿勢</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">質問</div>
            <div>
              <div class="say">「急ぎの時ほど、どこだけは“絶対に省略しない”ですか？」</div>
              <div class="note">安全優先か、スピード優先かが出る。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="bTitle">メモ（価値観・相性）</div>
      <div class="memo" contenteditable="true" id="valueMemo"></div>
    </section>

    <!-- SCENE 5 -->
    <section class="scene">
      <div class="sceneHead">
        <h2 class="sceneTitle">Scene 5｜勤務のすり合わせ（常勤・非常勤 共通の前提 → 条件確定）</h2>
        <span class="pill">10〜12分</span>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>まず言う（共通の前提）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「次に働き方の確認をさせてください。ここは曖昧にせず、現実的に続けられるかを一緒に見ますね。」</div>
              <div class="note">※先に宣言すると、質問が失礼に見えない。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「本園は365日開園なので、調理も“365日運営できる体制”が前提になります。出勤はシフトで回します。」</div>
              <div class="note">※ここで“365日＝毎日出勤ではない”を明確にする。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>常勤の場合（必須条件の確認）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「常勤でお願いする場合、<b>8:00〜18:00の枠</b>で、365日運営に対応できることがマストになります。」</div>
              <div class="note">※“枠で対応できる”＝毎日出勤ではない。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「ただ、365日ずっと出勤ではなくて、<b>365日シフトを作れる余地</b>がほしい、という意図です。」</div>
              <div class="note">※相手の誤解（毎日出勤）を先に潰す。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「それだけだと働きにくいと思うので、<b>希望休は月3日</b>取れる運用にしています。」</div>
              <div class="note">※“配慮はある”を明言して安心させる。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">質問</div>
            <div>
              <div class="say">「この条件（8-18の枠＋365日運営に対応＋希望休3日）で、現実的に続けられそうですか？」</div>
              <div class="note">深掘り：家庭事情／通勤／体力面／NG曜日の有無</div>
            </div>
          </div>
        </div>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>非常勤の場合（お願いしたい前提）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「非常勤の方にもお願いしたいのは、休みが<b>土日祝で毎回固定</b>になる形は避けたい、という点です。」</div>
              <div class="note">※理由をすぐ添える。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「そこが固定になると、他の職員が休めなくなってしまうので、調理職員同士で連携して、365日運営できる形に配慮してほしいです。」</div>
              <div class="note">※“協力のお願い”として伝える。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「お盆・年末年始・ゴールデンウィークも同じで、固定化ではなく、調理職員間で調整して回したいです。」</div>
              <div class="note">※ここは誤魔化さず先に出す（後出しNG）。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">質問</div>
            <div>
              <div class="say">「土日祝・大型連休も“毎回固定ではなく調整”という形で、協力できそうですか？」</div>
              <div class="note">深掘り：絶対NG日／月1回なら可能 等の落としどころ</div>
            </div>
          </div>
        </div>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>最後に確認（共通）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">質問</div>
            <div>
              <div class="say">「勤務できる時間帯は、具体的に何時〜何時ですか？（週何日まで可能ですか？）」</div>
              <div class="note">例：8-17／9-18／〜18／〜20時／週2〜5／土日可否</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">質問</div>
            <div>
              <div class="say">「遅番（〜18時枠）や土日祝に入る場合、帰宅手段や家庭側の都合は問題ないですか？」</div>
              <div class="note"><span class="w">地味に重要</span>：ここが破綻すると早期離職につながる。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="bTitle">メモ（条件の確定）</div>
      <div class="memo" contenteditable="true" id="condMemo">例）雇用：常勤／非常勤　時間：＿＿＿　週：＿＿＿　土日祝：＿＿＿　連休：＿＿＿　希望休：＿＿＿</div>
    </section>

    <!-- SCENE 6 -->
    <section class="scene">
      <div class="sceneHead">
        <h2 class="sceneTitle">Scene 6｜園からの説明（基準の明文化：安全・衛生・連携）</h2>
        <span class="pill">5分</span>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>言う（そのまま）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「本園は、段取りと安全が最優先です。急いでいても“安全と衛生”は絶対に崩しません。」</div>
              <div class="note">※ここで基準を明確にする。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「365日運営なので、個人プレーではなく、調理職員間の連携がとても大事になります。困ったら早めに相談する文化です。」</div>
              <div class="note">※“連携が評価される”を伝える。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「機器（スチコン等）も使うので、ルール化して運用しています。慣れるまでは一緒に進めます。」</div>
              <div class="note">不安を減らす言い方。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「最後にもう一度だけ。勤務条件は“お互いに無理がないか”が大事なので、気になる点があれば今の時点で言ってください。」</div>
              <div class="note">※ここで本音を引き出す。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="bTitle">メモ（相手の反応）</div>
      <div class="memo" contenteditable="true" id="explainMemo"></div>
    </section>

    <!-- SCENE 7 -->
    <section class="scene">
      <div class="sceneHead">
        <h2 class="sceneTitle">Scene 7｜厨房見学（任意）</h2>
        <span class="pill">5分</span>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>言う（そのまま）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「では厨房を簡単にご案内します。火・刃物・床の濡れがあるので足元だけ注意してください。」</div>
              <div class="note">※安全注意は“短く・明確に”。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「（案内しながら）ここがスチコンです／ここが保管です／ここが洗浄です。」</div>
              <div class="note">※説明はポイントだけ。現場の邪魔をしない。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">質問</div>
            <div>
              <div class="say">「見学してみて、不安な点はありましたか？」</div>
              <div class="note">現実的な視点があるか確認。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="bTitle">メモ（見学）</div>
      <div class="memo" contenteditable="true" id="tourMemo"></div>
    </section>

    <!-- SCENE 8 -->
    <section class="scene">
      <div class="sceneHead">
        <h2 class="sceneTitle">Scene 8｜締め・退出（最後の印象）</h2>
        <span class="pill">2分</span>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>言う（そのまま）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「本日はありがとうございました。結果は、<b>本日中（または明日）</b>にこちらからご連絡します。」</div>
              <div class="note">※“いつ連絡するか”を必ず言う。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">セリフ</div>
            <div>
              <div class="say">「最後に、聞き残したことはありませんか？（1つだけで大丈夫です）」</div>
              <div class="note">※質問時間を制限して、引き延ばさない。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">行動</div>
            <div>
              <div class="say">忘れ物確認 → お見送り</div>
              <div class="note">丁寧に、でも短く。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="bTitle">メモ（最後の印象／次アクション）</div>
      <div class="memo" contenteditable="true" id="endMemo">例）採用なら：体験調理／書類回収／初日案内　不採用なら：丁寧文面</div>
    </section>

    <!-- SCENE 9 -->
    <section class="scene">
      <div class="sceneHead">
        <h2 class="sceneTitle">Scene 9｜面接直後（園内処理：10分で終わらせる）</h2>
        <span class="pill">10分</span>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>行動（そのまま）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">行動</div>
            <div>
              <div class="say">面接メモを “判断根拠” で1分要約する（長文にしない）</div>
              <div class="note">例）「衛生観：強い／報連相：良い／大量調理：経験あり／連休：調整可／条件：合意」</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">行動</div>
            <div>
              <div class="say">共有は “必要最小限” にする（厨房責任者・事務・配置担当だけ）</div>
              <div class="note">※感想共有ではなく、配置とリスクに必要な情報のみ。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">行動</div>
            <div>
              <div class="say">次アクションを決める（①採用 ②体験調理 ③保留 ④不採用）</div>
              <div class="note">※「保留」は期限を決めないと腐る。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="bTitle">メモ（判断根拠：1分要約）</div>
      <div class="memo" contenteditable="true" id="postMemo"></div>
    </section>

    <!-- SCENE 10 -->
    <section class="scene">
      <div class="sceneHead">
        <h2 class="sceneTitle">Scene 10｜合否連絡（採用／保留／不採用）</h2>
        <span class="pill">5〜8分</span>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>採用：電話 or LINE（台本）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">採用</div>
            <div>
              <div class="say">「本日はありがとうございました。選考の結果、ぜひ一緒にお願いしたいと思いご連絡しました。」</div>
              <div class="note">※まず“感謝→結論”。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">採用</div>
            <div>
              <div class="say">「勤務の条件は、（勤務時間）・（週日数）・（土日祝・連休の調整）でお間違いないですか？ では次は初出勤（または体験）日程を決めましょう。」</div>
              <div class="note">※条件を最後にもう一回“確定”する。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">採用</div>
            <div>
              <div class="say">「当日は、動きやすい服装で、筆記具をお持ちください。持ち物はあとで文章でもお送りします。」</div>
              <div class="note">※口頭→文章の順で安心感が上がる。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>保留：連絡台本（期限を言う）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">保留</div>
            <div>
              <div class="say">「本日はありがとうございました。検討に必要な確認が一つあり、園内で調整してから改めてご連絡します。」</div>
              <div class="note">※濁さない。理由は“園内調整”で十分。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">保留</div>
            <div>
              <div class="say">「遅くとも（◯月◯日）までに必ずご連絡しますので、少々お時間ください。」</div>
              <div class="note">※期限がない保留は不信になる。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>不採用：連絡台本（丁寧に・短く）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">不採用</div>
            <div>
              <div class="say">「本日はお時間をいただきありがとうございました。慎重に検討した結果、今回はご縁に至りませんでした。」</div>
              <div class="note">※理由の詳細は言わない（揉める芽を摘む）。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">不採用</div>
            <div>
              <div class="say">「お話を伺い、誠実なお気持ちを感じました。今後のご活躍を心より応援しております。」</div>
              <div class="note">※最後の印象が園の評判になる。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="bTitle">メモ（連絡内容・日時）</div>
      <div class="memo" contenteditable="true" id="contactMemo">例）12/17 15:30 電話（採用）／初出勤：1/6 8:30</div>
    </section>

    <!-- SCENE 11 -->
    <section class="scene">
      <div class="sceneHead">
        <h2 class="sceneTitle">Scene 11｜採用後の段取り（初出勤までにやること）</h2>
        <span class="pill">15分</span>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>園内側：準備（台本）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">園内</div>
            <div>
              <div class="say">初日の担当（教える人）を決める：厨房責任者／補助1名（可能なら）</div>
              <div class="note">※初日から“放置”が一番危険。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">園内</div>
            <div>
              <div class="say">初日の作業範囲を決める：洗浄・清掃／下処理／配膳補助 など（安全重視）</div>
              <div class="note">※いきなり全工程は振らない。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">園内</div>
            <div>
              <div class="say">衛生ルール・機器ルールの「最初に教える3つ」を決める</div>
              <div class="note">例）手洗いタイミング／交差汚染／温度・記録</div>
            </div>
          </div>
        </div>
      </div>

      <div class="block">
        <div class="bTitle">
          <span>本人へ送る：初日案内（台本）</span>
          <label class="check"><input type="checkbox">実施</label>
        </div>

        <div class="lines">
          <div class="line">
            <div class="tag">案内</div>
            <div>
              <div class="say">「初日は（時間）に来園ください。服装は動きやすいもので、室内履きが必要です（必要なら）。」</div>
              <div class="note">※園のルールに合わせて編集。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">案内</div>
            <div>
              <div class="say">「持ち物：筆記具／印鑑（必要なら）／身分証（必要なら）／メモ帳」</div>
              <div class="note">※契約書類があるならここに追加。</div>
            </div>
          </div>

          <div class="line">
            <div class="tag">案内</div>
            <div>
              <div class="say">「当日は、安全と衛生の確認から入ります。分からないことはすぐ聞いてください。」</div>
              <div class="note">※“質問歓迎”を明言すると事故が減る。</div>
            </div>
          </div>
        </div>
      </div>

      <div class="bTitle">メモ（初日：担当／内容）</div>
      <div class="memo" contenteditable="true" id="firstDayMemo">担当：＿＿＿／初日の範囲：＿＿＿／教える3つ：＿＿＿</div>
    </section>

  </div>

  <div class="footer">
    <b>最後に園内で残す一文（判断根拠）：</b>
    「この人は、<span class="k">安全と段取り</span>を優先できるか／<span class="k">報連相</span>ができるか／<span class="k">365日運営への協力</span>ができるか」。
  </div>

</div>

<script>
  function setToday(){
    const d = new Date();
    const y = d.getFullYear();
    const m = d.getMonth()+1;
    const day = d.getDate();
    const w = ["日","月","火","水","木","金","土"][d.getDay()];
    document.getElementById("dateField").innerText = `${y}年${m}月${day}日（${w}）`;
  }
</script>
</body>
</html>
