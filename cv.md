# Vladimir Sabaev

## Contacts:

---

- **E-mail:** vladimir8sabaev@mail.ru
- **Phone:** +79993488190
- **GitHub account:** [vladimir8sabaev](https://github.com/vladimir8sabaev)
- **Telegram:** [vladimirsabaev](https://t.me/vladimirsabaev)
- **VK:** [vladimirsabaev](https://vk.com/vladimirsabaev)

## About section:

---

    I am 24 yr old BMSTU student and circuit designer from Skolkovo, Moscow, my current job has become a bit boring to me, so i desided to try web development as a completely different activity. My global goal is to find a job that burns a fire inside

    - Pros:
    - strong base from uni
    - enough time for a deep dive
    - team playing skills
    - commercial development experience (Automotive PCB's)

## Skills

---

    - HTML
    - CSS (Bootstrap, PostCss)
    - SCSS/ SASS (prefer SCSS)
    - JavaScript (basics, ES6+ features, DOM model, JSON, fetch, promise, call context (this), ES6 modules, anync JS, event loop, macro- microtasks)
    - GIT basics
    - Additional tech (npm, webpack with dev/prod and all-in-one amazing config, JS libraries (ky for fetching, chart.js for charts))

## Code example

```
async function stockData() {
		const data = await ky.get("http://localhost:3000/switches").json();
		const switchName = data.map(function (item) {
			return item.name;
		});
		const switchNoise = data.map(function (item) {
			return item.noise;
		});
		const switchFeeling = data.map(function (item) {
			return item.feeling;
		});
}
```
