**THIS IS A FORK OF [input-moment](https://github.com/wangzuo/input-moment) USED AT HIVEBEAT**

# input-moment
React datetime picker powered by [momentjs](http://momentjs.com)

The design is from https://dribbble.com/shots/1439965-Due-Date-and-Time-Picker.

The icon is from [ionicons](http://ionicons.com/).

### Installation
``` sh
npm i hb-input-moment --save
```

**Notice:** This module requires [moment](https://www.npmjs.com/package/moment) as a [peerDependency](https://docs.npmjs.com/files/package.json#peerdependencies).

### Demo
http://wangzuo.github.io/input-moment

### Usage

#### Basic example
``` javascript
<InputMoment
  moment={this.state.moment}
  onChange={this.handleChange}
  onSave={this.handleSave}
/>
```

#### Props
| Prop          | Description                                       | Default                                           |
|---------------|---------------------------------------------------|---------------------------------------------------|
| dateOnly      | Boolean. If it should show only the date picker.  | `false`                                           |
| timeOnly      | Boolean. If it should show only the time picker.  | `false`                                           |
| prevMonthIcon | String. Class string for the previous month icon. | 'ion-ios-arrow-left'                              |
| nextMonthIcon | String. Class string for the next month icon.     | 'ion-ios-arrow-right'                             |
| weeks         | Array. Days of the week in order.                 | `['Sun', 'Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat']` |
| locale        | String. Locale to display date time in.           | 'en'                                              |
| saveString    | String. String so display on the save button.     | 'Save'                                            |


Check [app.js](https://github.com/wangzuo/input-moment/blob/master/example/app.js) for a working example.

### Development
- npm install
- npm start
- http://localhost:8888

### License
ISC
