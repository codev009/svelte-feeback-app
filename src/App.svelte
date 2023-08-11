<script>
  import FeedbackList from "./components/FeedbackList.svelte";

  let feedback = [
    {
      id: 1,
      rating: 10,
      text: "lorem ipsum",
    },
    {
      id: 2,
      rating: 9,
      text: "lorem ipsum",
    },
    {
      id: 3,
      rating: 8,
      text: "lorem ipsum",
    },
  ];
</script>

<main>
  <FeedbackList {feedback} />
</main>
