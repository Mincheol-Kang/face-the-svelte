<script>
import {
  getRegExp,
  engToKor,
  korToEng,
  correctPostpositions,
  explode,
  implode,
  getPhonemes,
} from 'korean-regexp';

let inputText = '';

</script>

<div class="content">
    정규식 <input bind:value={inputText}>
    <div>
        {getRegExp(inputText)}
    </div>

</div>

<style>
    input {
        width: 100%;
    }
</style>
