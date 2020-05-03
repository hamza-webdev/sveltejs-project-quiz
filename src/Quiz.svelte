<script>
   // export const quizName = "hamza Quiz"; // const: can't change it an export in component file App.svelte
   export let quizName = "hamza Quiz";

   export let title = "";
   let a = 0;
   let b = 0;
</script>

<div>
    <h2>Voici liste de quiz a répondre :</h2>
    <h3>{quizName}</h3>
    <h3>{title}</h3>
    <input bind:value={title} type="text">
    <hr>
    a: <input type="number" bind:value={a} >
     b: <input type="number" bind:value={b} >
    <h4><u>Some a +b = { a + b}</u></h4>
</div>