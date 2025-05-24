echo "# My-crypto-" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Mahiany123ussamuel/My-crypto-.git
git push -u origin mainuseEffect(() => {
  fetch("/.netlify/functions/getNews")
    .then(res => res.json())
    .then(data => {
      setNews(data.Data || []);
      setLoading(false);
    })
    .catch(() => setLoading(false));
}, []);{
  "dependencies": {
    "node-fetch": "^2.6.7"
  }
}https://github.com/Mahiany123ussamuel/My-crypto-.gitecho "# My-crypto-" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Mahiany123ussamuel/My-crypto-.git
git push -u origin mainREADME.md
