```jsx
import 'styles.css';

function LiveCode() {
  const [clicks, setClicks] = useState(0);
  return (
    <div>
      <p>Counter value: {clicks}</p>
      <button onClick={() => setClicks(clicks + 1)}>
        click here
      </button>
    </div>
  );
}
```


### Live result
  <a align="center" href="https://halb.it/readme-games/action.php?g=live-code-github&a=increment">
    <img src="https://halb.it/readme-games/resources.php?g=live-code-github&r=htmlbt">
  </a>
    <img src="https://halb.it/readme-games/resources.php?g=live-code-github&r=counter">
