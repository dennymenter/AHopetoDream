<!-- this will be a card that I will reuse for FAQs -->

<script>
    export let question = "(no question provided)";
    export let answer = "(no answer provided)";
</script>

<div class="border-slate-900 border-solid border m-2 max-w-xs rounded-xl shadow-xl hover:backdrop-sepia ">
    <div class="m-2 uppercase">{question}</div>
    <div class="m-2">{answer}</div>
</div>