## Hi there 👋

```angular
import { Routine } from '@week';

@Component({
  template: `
	  <h2>Lets make a day productive!</h2>
	  <button (click)="openVS/VSCode()">OK</button>
	  `
   })

export class DailyComponent {
  mood = 'normal';
  openVSorVSCode(){
    this.mood = 'great';
  }
}
```
