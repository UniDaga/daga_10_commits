## **Bypass Zama Dev Guild "10 Commits Before 10 July" Task**
After following this guide you will have: 20 commits on your github before 30 June

There are currently 2 ways to bypass this task
using codespace terminal: short but works for few people
using wsl/ubuntu: works for everyone we will be using second method here to onboard more people
Instructions

1. ## Create a New Repository
<div id="textToCopy" style="border:1px solid #ccc; padding:10px; cursor:pointer;">
2. Open Ubuntu<br>
3. Clone your GitHub repo<br>
In Newly Created GitHub Repo click the green &lt;&gt; Code button copy the HTTPS link (looks like: https://github.com/username/repo.git)
</div>

<script>
document.getElementById("textToCopy").addEventListener("click", () => {
    const text = document.getElementById("textToCopy").innerText;
    navigator.clipboard.writeText(text).then(() => {
        alert("Copied all text to clipboard!");
    }).catch(err => {
        console.error("Failed to copy: ", err);
    });
});
</script>


