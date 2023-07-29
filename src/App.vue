<script setup lang="ts">
import Nav from './components/Nav.vue'
import AddCalendarBirthday from './components/AddCalendarBirthday.vue'
</script>

<template>
  <Nav />
  <main>
    <div class="pure-g">
      <div class="pure-u-1-1 pure-u-sm-1-1 pure-u-md-1-3">
        <h1 class="name-obj" lang="ja"><ruby>潤<rt>うる</rt></ruby><ruby>羽<rt>は</rt></ruby> るしあ</h1>
        <small lang="en">
          URUHA, Rushia
        </small>
      </div>
      <div class="pure-u-1-1 pure-u-sm-1-1 pure-u-md-2-3 user-desc">
        <h2><span lang="en">Details</span> / <span lang="ja">詳細</span></h2>
        <dl>
          <dt><span lang="en">Belong</span> / <span lang="ja">所属</span></dt>
          <dd><span lang="en">hololive production</span> / <span lang="ja">ホロライブプロダクション</span></dd>
          <dt><span lang="en">Birthday</span> / <span lang="ja">誕生日</span></dt>
          <dd>
            <span lang="en">January 22</span> / <span lang="ja">1月22日</span>
            <AddCalendarBirthday />
          </dd>
          <dt><span lang="en">Activity begin date</span> / <span lang="ja">活動開始日</span></dt>
          <dd><span lang="en">July 8, 2019</span> / <span lang="ja">2019年7月8日</span></dd>
          <dt><span lang="en">Activity end date</span> / <span lang="ja">活動終了日</span></dt>
          <dd><span lang="en">February 24, 2022</span> / <span lang="ja">2022年2月24日</span></dd>
        </dl>
        <h2><span lang="en">Links</span> / <span lang="ja">リンク集</span></h2>
        <dl lang="en">
          <dt>Wikidata</dt>
          <dd><a href="https://www.wikidata.org/wiki/Q90815761">Q90815761</a></dd>
          <dt>MusicBrainz</dt>
          <dd><a href="https://musicbrainz.org/artist/070e2866-c3ce-43da-b7e1-c9958eb3b23c">MusicBrainz Artist Page</a></dd>
        </dl>
        <hr />
        潤羽るしあ ファンサイト, 当該人物に関する一切の権利は持っておりません。
      </div>
    </div>
  </main>
</template>

<style scoped>
.name-obj {
  margin-bottom: 3px;
}

.user-desc h2,
.user-desc h3,
.user-desc h4,
.user-desc h5,
.user-desc h6 {
  border-left: 3px solid var(--theme-color);
  padding-left: 10px;
}

dl>dt, dl>dd {
  display: block;
  margin: 0;
}

dl>dt {
  font-weight: bold;
  margin-top: 5px;
  margin-bottom: 2px;
}

dl>dd {
  margin-left: 15px;
}
</style>
