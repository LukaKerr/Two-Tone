# two-tone

Compile `/src` by running `sass src/style.scss dist/style.css` from `/two-tone`.

Watch all `.scss` file changes by running `sass --watch src/style.scss:dist/style.css` from `/two-tone`.

### Different Body Themes

```html
<body class="dark"> <!-- Dark Theme -->
<body class="narrow"> <!-- Narrow Theme -->
```

### Standard Navigation

The stardard nav bar can be fixed by adding class `fixed`, can be made into a dark theme by adding class `dark` or centered by adding class `centered`. These classes can be combined, for example to create a centered fixed dark nav bar.

```html
<div class="nav">
	<ul>
		<a href="#" class="nav-logo">Website Name</a>
		<a href="#">Item #1</a>
		<a href="#">Item #2</a>
		<a href="#">Item #3</a>
		<a href="#">Item #4</a>
		<a href="#">Item #5</a>
		<div class="dropdown">
		  <a href="#">Dropdown #1</a>
		  <div class="dropdown-content">
	    	<a href="#">Item #1</a>
	    	<a href="#">Item #2</a>
	    	<a href="#">Item #3</a>
	  	</div>
		</div>
	</ul>
</div>
```

### Mobile Navigation

```html
<div class="mob-nav"> <!-- Dark Mode: <div class="mob-nav dark"> -->
	<input type="checkbox">
	<span></span>
	<span></span>
	<span></span>
	<ul class="mob-menu">
		<a href="#"><li>Item #1</li></a>
		<a href="#"><li>Item #2</li></a>
		<a href="#"><li>Item #3</li></a>
		<a href="#"><li>Item #4</li></a>
		<a href="#"><li>Item #5</li></a>
	</ul>
</div>
```

### Multiple Sections

```html
<div class="sec"> <!-- Dark Mode: <div class="sec dark"> -->
	...
</div>

<div class="sec">
	...
</div>

<div class="sec">
	...
</div>
```

### Variable Width Columns

```html
<ul class="col"> <!-- Dark Mode: <ul class="col dark"> -->
	<li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam posuere rutrum orci, quis accumsan quam mollis vel.</li>
	<li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam posuere rutrum orci, quis accumsan quam mollis vel.</li>
	<li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam posuere rutrum orci, quis accumsan quam mollis vel.</li>
	<!-- Can add more <li> for more columns -->
</ul>
```

### Column options

```html
<ul class="col pd"> <!-- Spacing -->
<ul class="col center"> <!-- Centered text -->
<ul class="col clear"> <!-- Transparent Columns -->
<ul class="col dark"> <!-- Dark theme -->
<ul class="col pd dark center"> <!-- Combinations are available -->
```

### Tabs

```html
<div class="tabs">
	<div class="tab">
		<input type="radio" id="t1" name="tg1" checked>
		<label for="t1">Tab One</label>

		<div class="content">
			<p>Content for Tab One</p>
		</div> 
	</div>

	<div class="tab">
		<input type="radio" id="t2" name="tg1">
		<label for="t2">Tab Two</label>

		<div class="content">
			<p>Content for Tab Two</p>
		</div> 
	</div>

	<div class="tab">
		<input type="radio" id="t3" name="tg1">
		<label for="t3">Tab Three</label>

		<div class="content">
			<p>Content for Tab Three</p>
		</div> 
	</div>
</div> 
```

### Padding/Margin Options

Add margins to most elements by adding the pd class

```html
<input class="pd">
<ul class="col pd"></ul>
<div class="alert success pd">Success</div>
<div class="tabs pd"></div>
<input class="pd">
<textarea class="pd"></textarea>
<div class="panel pd"></div>

<!-- Make element take up full width of page -->
<ul class="col full"></ul>
```

### Alert Banners

```html
<div class="alert success">Success</div>
<div class="alert warning">Warning</div>
<div class="alert error">Error</div>
<div class="alert info">Info</div>
```

### Buttons

There are many different combinations of buttons available. Combine various class names to get different button types.
<br><br>
Button class names include:
<br>

<li>tablet</li>
<li>square</li>
<li>quote</li>
<li>warning</li>
<li>close</li>
<li>push</li>
<li>fill</li>
<li>sml</li>
<li>med</li>
<li>lrg</li>
<li>xlrg</li>
<li>red</li>
<li>blue</li>
<li>green</li>
<li>yellow</li>
<li>orange</li>
<li>purple</li>
<li>black</li>
<li>aqua</li>
<li>nocol</li>
<li>nobor</li>
<li>caps</li>
<li>sm-caps</li>


```html
<button class="btn tablet red sm-caps">Tablet Button</button>
<button class="btn square caps">Square Button</button>
<button class="btn aqua">Button</button>
<button class="btn push lrg sm-caps">Push Button</button>
<button class="btn tablet med nocol orange fill sm-caps">Tablet Filling Button</button>
<button class="btn quote sm-caps med">Quote</button>
<button class="btn warning lrg">Warning!</button>
<button class="btn close lrg">Close</button> 
```

### Panel

```html
<div class="panel">
	<h1>Hello World</h1>
	<p>This is some text</p>
	<button class="btn tablet">Go!</button>
</div>
```

### Grid

Use the following syntax to create a responsive grid.
<br><br>
Add either `grid-2`, `grid-3`, `grid-4` or `grid-6` depending on how many grid objects you want per row.

```html
<div class="grid">
	<div>
		<div class="content"></div>
	</div>
</div>

<div class="grid grid-2">
	<div>
		<div class="content"></div>
	</div>
	<div>
		<div class="content"></div>
	</div>
</div>
```

### Footer

```html
<div class="footer">
	...
</div> 
```