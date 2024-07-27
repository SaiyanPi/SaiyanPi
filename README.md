## Hi there 👋

```ts
import { Routine } from '@week';

@Component({
  template: `
	  <h2>Lets make a day productive!</h2>
	  <button (click)="openVSorVSCode()">OK</button>
	  `
   })

export class DailyRoutine {
  mood = 'normal';
  openVSorVSCode(){
    this.mood = 'great';
  }
}
```
