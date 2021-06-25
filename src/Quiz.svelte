<script>
  import QuizQuestion from "./QuizQuestion.svelte";

  export let quizName = "Stephen Quiz";
  let title = "hello";
</script>

<div>
  <h2>{quizName}</h2>
  <h4>{title}</h4>
  <input bind:value={title} type="text" />
  <QuizQuestion answer="hello" />
</div>
