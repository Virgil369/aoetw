<template>
  <div class="container">
    <div class="row padtop">
      <div class="col-md-12">
        <h1>自負的野心</h1>
        <div class="hrn1"></div>
      </div>
      <div class="col-md-8">
        <div class="n1">
          <p>
            自負的野心是<nuxt-link to="/games/delw">西方霸主</nuxt-link
            >DLC新增的<nuxt-link to="/batt">戰役</nuxt-link>中，<nuxt-link
              to="/batts/Edward_Longshanks"
              >長腿愛德華</nuxt-link
            >的第一關。
          </p>
        </div>
        <h2>玩家</h2>
        <div class="hrn1"></div>
        <div class="n1">
          <h3>基本資訊</h3>
          <table class="table-bordered" width="100%">
            <tr>
              <td class="tc1" width="14%">起始時代：</td>
              <td class="tc2" width="28%">
                <nuxt-link to="/techs/age/Castle_Age">城堡時代</nuxt-link
                >（標準難度）<br /><nuxt-link to="/techs/age/Feudal_Age"
                  >封建時代</nuxt-link
                >（其他難度）
              </td>
              <td class="tc1" width="14%">起始資源：</td>
              <td class="tc2">
                無
              </td>
              <td class="tc1" width="14%">人口上限：</td>
              <td class="tc2" width="5%">125</td>
            </tr>
          </table>

          <h3>AI</h3>
          <table class="table-bordered" width="100%">
            <tr>
              <td class="tc4" colspan="4" style="background: #2980b9;">
                玩家本身
              </td>
            </tr>
            <tr>
              <td class="tc6" width="14%">
                <div class="p2"></div>
                玩家1
              </td>
              <td class="tc6" colspan="6">
                <nuxt-link to="/civs/Britons">不列顛人</nuxt-link>（紅色)
              </td>
            </tr>

            <tr>
              <td class="tc4" colspan="4" style="background: #27ae60;">同盟</td>
            </tr>
            <tr>
              <td class="tc6" width="14%">
                <div class="p7"></div>
                玩家2
              </td>
              <td class="tc6">伍斯特（灰色）不列顛人</td>
              <td class="tc6" width="14%">
                <div class="p5"></div>
                玩家6
              </td>
              <td colspan="3" class="tc6">
                赫里福德（青色）<nuxt-link to="/civs/Sicilians"
                  >西西里人</nuxt-link
                >
              </td>
            </tr>
            <tr>
              <td class="tc4" colspan="4" style="background: #ea6153;">中立</td>
            </tr>
            <tr>
              <td class="tc6" width="14%">
                <div class="p4"></div>
                玩家7
              </td>
              <td class="tc6">威爾斯（黃色）不列顛人</td>
            </tr>

            <tr>
              <td col class="tc4" colspan="4" style="background:#ea6153;">
                敵對
              </td>
            </tr>
            <tr>
              <td class="tc6" width="14%">
                <div class="p1"></div>
                玩家3
              </td>
              <td class="tc6">男爵軍隊（藍色）西西里人</td>
              <td class="tc6" width="14%">
                <div class="p8"></div>
                玩家4
              </td>
              <td colspan="3" class="tc6">格洛斯特（橙色）不列顛人</td>
            </tr>
            <tr>
              <td class="tc6" width="14%">
                <div class="p3"></div>
                玩家5
              </td>
              <td class="tc6">
                凱尼爾沃思（綠色）不列顛人
              </td>
            </tr>
          </table>

          <br />
          <dl class="dl-horizontal">
            <dt>開場：</dt>
            <dd>
              長腿愛德華、吉爾伯特‧德‧克萊爾、<nuxt-link to="/units/Man-at-Arms"
                >裝甲步兵</nuxt-link
              >x2
            </dd>
          </dl>
          <h3>任務</h3>
          <div class="hrn1"></div>
          <div class="n1">
            <ul>
              <li>長腿愛德華必須活著。（逃至伍斯特前）</li>
              <li>吉爾伯特‧德‧克萊爾必須活著。（逃至伍斯特前）</li>
              <li>
                愛德華和吉爾伯特必須逃離赫里福德，並在附近的旅館騎上馬匹。（逃至伍斯特前）
              </li>
              <li>
                愛德華和吉爾伯特必須在伍斯特鎮（2，灰色）尋求幫助。（逃至伍斯特前）
              </li>
              <li>建立您的部隊‧西蒙很快就會得知您逃跑的消息。</li>
              <li>
                打敗或征服5個對手的其中3個（男爵軍隊、赫里福德、格洛斯特、凱尼爾沃斯、威爾斯）
              </li>
            </ul>
            <p>次要任務</p>
            <ul>
              <li>
                摧毀對手的<nuxt-link to="/building/Town_Center"
                  >城鎮中心</nuxt-link
                >或<nuxt-link to="/building/Castle">城堡</nuxt-link
                >來征服他們，而不是將其徹底消滅。
              </li>
              <li>
                在西蒙‧德‧孟德爾福發動進攻之前，攻擊小西蒙必在凱尼爾沃斯附近擊敗他的部隊。
              </li>
            </ul>
          </div>
          <h3>提示</h3>
          <div class="hrn1"></div>
          <div class="n1">
            <ul>
              <li>
                愛德華勛爵只能發展到<nuxt-link to="/techs/age/Castle_Age"
                  >城堡時代</nuxt-link
                >。人口上限為125人。
              </li>
              <li>
                您可以透過以下三種方式逃離赫里福德：偷一艘破損的船、從<nuxt-link
                  to="/building/Stone_Wall"
                  >城牆</nuxt-link
                >上的<nuxt-link to="/building/Watch_Tower">箭塔</nuxt-link
                >跳下去，或者是用最危險的方式，從正門殺出一條血路逃出生天。
              </li>
              <li>
                積極進攻。某些對手前期時很脆弱，盡早出擊可以使他們崩潰，但如果放任他們發展則會給您造成大麻煩。
              </li>
              <li>
                能征服就不要摧毀。夷平城鎮中心和城堡可以征服格洛斯特、凱尼爾沃斯、赫里福德和威爾斯人，使他們轉而支持您。
              </li>
              <li>
                男爵軍隊將會死戰到底，但他們的補給是由當地的城鎮提供的。每征服一個城鎮就意味著減少這個致命的敵人可獲得的資源。
              </li>
            </ul>
          </div>
          <h3>斥候</h3>
          <div class="hrn1"></div>
          <div class="n1">
            <ul>
              <li>
                愛德華勛爵（1，紅色）目前被囚禁在赫里福德，但一個料想不到的盟友，吉爾伯特‧德‧克萊爾已經帶著他的護衛抵達了那裡，準備解救愛德華。
              </li>
              <li>
                伍斯特（2，灰色）是塞文河的一個小鎮，位於地圖中央。那裡的人民很同情愛德華，如果愛德華能抵達那裡，他們會加入愛德華的陣營。
              </li>

              <li>
                格落斯特（4，橙色）坐落於塞文河的更南邊。格洛司特前期很脆弱且缺乏防禦，但經過一段時間的發展就能以<nuxt-link
                  to="/units/Long_Swordsman"
                  >長劍兵</nuxt-link
                >和<nuxt-link to="/units/Elite_Skirmisher">戰矛兵</nuxt-link
                >騷擾愛德華。
              </li>
              <li>
                凱尼爾沃斯(5，綠色)是東北方的一個小城堡。其中駐紮的<nuxt-link
                  to="/units/Spearman"
                  >長槍兵</nuxt-link
                >和<nuxt-link to="/units/Light_Cavalry">輕騎兵</nuxt-link
                >只是象徵性的威脅，但傳言小西蒙在附近駐紮了一支大型部隊。
              </li>
              <li>
                赫里福德（6，青色）是一個戒備森嚴的城鎮，為於威河和拉格河的交匯處。他們會派出一支由<nuxt-link
                  to="/units/Serjeant"
                  >薩金特衛兵</nuxt-link
                >和<nuxt-link to="/units/Crossbowman">弩兵</nuxt-link
                >組成的強大軍隊，並準備<nuxt-link to="/units/Mangonel"
                  >輕型投石車</nuxt-link
                >來打擊愛德華的根據地。
              </li>
              <li>
                男爵軍隊（3，藍色）是叛軍中犀利勇猛的精銳部隊，他們在數個地點駐紮。他們目前暫且沒有動作，但當他們發動進攻之時，您得準備好面對成群的<nuxt-link
                  to="/units/Knight"
                  >騎士</nuxt-link
                >和<nuxt-link to="/units/Man-at-Arms">裝甲步兵</nuxt-link>。
              </li>
              <li>
                西邊和西北邊是威爾斯人的地盤（7，黃色）。他們致命的<nuxt-link
                  to="/armor/Armor_Class_Spearman"
                  >長槍兵</nuxt-link
                >、<nuxt-link to="/units/Skirmisher">矛兵</nuxt-link
                >、<nuxt-link to="/units/Longbowman">長弓兵</nuxt-link
                >和帶著<nuxt-link to="/units/Battering_Ram"
                  >輕型衝撞車</nuxt-link
                >開始進攻。
              </li>
            </ul>
          </div>
          <h3>攻略</h3>
          <div class="hrn1"></div>
          <ul>
            <li>
              首先必須逃出城市到<nuxt-link to="/building/Stable">馬廄</nuxt-link
              >（逃出後赫里福德會馬上轉敵對），按提示說的有三種方法（要從<nuxt-link
                to="/building/Watch_Tower"
                >箭塔</nuxt-link
              >逃出去得先解決守軍），到<nuxt-link to="/building/Stable"
                >馬廄</nuxt-link
              >後單位全部變成<nuxt-link to="/armor/Armor_Class_Cavalry"
                >騎兵</nuxt-link
              >不會<nuxt-link to="/Regeneration">回血</nuxt-link
              >）。逃出後得到一筆資源，並有15分鐘可以發展。發展經濟的同時建立兵種，先訓練騎士約15隻並升級<nuxt-link
                to="/techs"
                >科技</nuxt-link
              >，有多的資源再造長槍兵和弩兵或長弓兵，以及<nuxt-link
                to="/units/Battering_Ram"
                >衝車</nuxt-link
              >四至五台。15分鐘後敵人會察覺愛德華已逃走，並得知30分後藍色會攻來，勝利條件為打敗三個敵人就行，只要解決掉城鎮中心和城堡即可。
            </li>
            <li>
              先進攻南方橘色，用騎士們加上兩隻<nuxt-link to="/units/hero"
                >英雄</nuxt-link
              >騎兵不要管迎擊的軍隊直撲城鎮中心，可以立刻先解決一個敵人（吉爾伯特會先行離開）；次要目標是西北方黃色，有一座城堡和城鎮中心，騎士隊一樣直接先爆掉城鎮中心阻止敵人升級時代，接著派出衝車進攻城堡，征服第二個目標。最後的目標是綠色，前方有一大群的有群藍色的騎兵和<nuxt-link
                to="/units/Infantry_Units"
                >步兵</nuxt-link
              >守著，在陣地前蓋城堡掩護，並派出大量的長槍兵和<nuxt-link
                to="/units/Archer"
                >弓兵</nuxt-link
              >，並取得成就「毫無風度的實用主義者」（30分時限內擊破）。再來就把衝車推出去夷平綠色城堡，本關隨即結束。
            </li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <table class="table-bordered" width="100%">
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">自負的野心</div>
            </td>
          </tr>
          <tr>
            <td colspan="2">
              （地圖待補）
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">戰役資訊</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">版本</td>
            <td class="unit4">
              <nuxt-link to="/games/delw">西方霸主</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3">戰役</td>
            <td class="unit4">
              <nuxt-link to="/batts/Edward_Longshanks">長腿愛德華</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit3"><nuxt-link to="/civs">文明</nuxt-link></td>
            <td class="unit4">
              <nuxt-link to="/civs/Britons">不列顛</nuxt-link>
            </td>
          </tr>
          <tr>
            <td class="unit" colspan="2" style="background-color:#375d96;">
              <div class="unititle2">戰役關卡編號</div>
            </td>
          </tr>
          <tr>
            <td class="unit3">章節</td>
            <td class="unit4">
              長腿愛德華第一章
            </td>
          </tr>
          <tr>
            <td class="unit3">上一關</td>
            <td class="unit4">N/A</td>
          </tr>
          <tr>
            <td class="unit3">下一關</td>
            <td class="unit4">
              <nuxt-link to="/batt/A_Man_of_God">上帝的子民</nuxt-link>
            </td>
          </tr>
        </table>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: 'allbatt',
  components: {}
}
</script>
<style></style>
