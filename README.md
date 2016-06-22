# MEAN Stack Plotly.js (https://github.com/kaufmann42/meanjs-plotly) 
# ORIGINAL: (https://github.com/alonho/angular-plotly)

## Usage

Install with bower:

```bash
bower install plotly --save
bower install meanjs-plotly --save
```

Include angular, plotly and meanjs-plotly:

```html
To your env/all.js file add:
js: [
  'public/lib/angular-plotly/src/angular-plotly.js',
  'public/lib/plotlyjs/plotly.js'
],
```

Add a chart:

```html
<plotly pdata="data" playout="layout" poptions="options"></plotly>
```

The values expected for `pdata`, `playout` and `poptions` can be found in [plotly's documentation](https://plot.ly/javascript/).
