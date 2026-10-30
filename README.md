<title>Cofre Numérico</title>
<meta name="claude:viewport-fit-sides" content="cover">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=JetBrains+Mono:wght@500;700&display=swap">
<style>
  /* Layout: um cartão central de cofre, campo de senha no topo e teclado numérico embaixo. */
  :root {
    --bg: #e9eef1;
    --card: #f7f9fa;
    --fg: #14202b;
    --muted: #5b6b78;
    --line: #cdd7de;
    --key: #ffffff;
    --accent: #0f6e6e;
    --accent-fg: #ffffff;
    --ok: #1b7f4b;
    --ok-bg: #dff3e7;
    --bad: #b3261e;
    --font-body: "DM Sans", system-ui, -apple-system, "Segoe UI", sans-serif;
    --font-num: "JetBrains Mono", ui-monospace, "SF Mono", Menlo, monospace;
  }
  @media (prefers-color-scheme: dark) {
    :root:not([data-theme="light"]) {
      --bg: #0d1418;
      --card: #141d23;
      --fg: #e6edf0;
      --muted: #8fa1ac;
      --line: #27343d;
      --key: #1b2830;
      --accent: #4fc3b5;
