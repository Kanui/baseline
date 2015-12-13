# BaselineCSS

Baseline is a vertical rythm system (ou vertical grid system) based on pixel-perfect concepts to develop views that needs a vertical size patterns.

The baseline rethink the common baseline property. With this lib the "baseline" is a specific vertical area and your content can't pass this limit.

### Installation
Download the baseline for your favorite format (SASS or SCSS) and put in your css directory.

### Configuration
First of all, you (and your designer) needs to decide the **line (or row) height** `$bl` and the **max height (max number of rows)** `$bl-max-rows`.


*baseline.sass*

	/* Set your baseline here */
	$bl: {YOUR_ROW_HEIGHT_HERE}

	/* Set your max number of rows here */
	$bl-max-rows: {YOUR_MAX_NUMBER_OF_ROWS_HERE}

For example, if you set `$bl = 10` and `$bl-max-rows = 80`, the baseline will create 80 classes (`.bl-2`, `.bl-3`... `.bl-80`), **padding + margin** classes (`.bl-margin-t-2`, `.bl-padding-b-3` and `.bl-fluid-4`), the **typo size** classes and the top height size will be 800px.

### Examples
Visit: <http://kanui.github.io/baseline> for examples.

### Contribute
See our issues list or fork this repo and pull us a improvement.

### Contact
The Baseline was created at [**Kanui**](http://github.com/kanui/queroserkanui) lab but the main sponsors of the project are [@maclovin](http://github.com/maclovin) and [@filipekiss](http://github.com/filipekiss).
### Version

0.4.2

### License
MIT
