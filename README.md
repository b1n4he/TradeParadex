# TradeParadex

~~~javascript
const trade = async () => {
    document.getElementsByClassName("Button-sc-15x9v5r-0")[1].click();
    await new Promise((resolve) => setTimeout(resolve, 300));
    document.getElementsByClassName("ButtonLink-sc-7gh1nc-0")[0].click();
    await new Promise((resolve) => setTimeout(resolve, 300));
    document.getElementsByClassName("Button-sc-15x9v5r-0")[3].click();
    await new Promise((resolve) => setTimeout(resolve, 300));
};

setInterval(trade, 3000);
~~~
