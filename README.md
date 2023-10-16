# Grid System with SCSS (Sass)

This is a customizable and responsive grid system created using SCSS (Sass), which allows you to quickly set up grid layouts for your web projects. The system is based on variables for grid width and gutter spacing, making it easy to adapt to your specific needs.

## Features

- Customizable grid width.
- Adjustable gutter spacing.
- Responsive layout options for different column sizes.
- SCSS mixin for clearfix to ensure proper clearing of floated elements.

## Getting Started

Follow these steps to use the grid system in your project:

1. Clone the repository to your local machine.
```sh
git clone https://github.com/yourusername/your-repo.git
```

2. Customize the variables:

- Open the _grid.scss file.
- Modify the values of $grid-width, $gutter-vertical, and $gutter-horizontal to match your project's requirements.

3. Include the _grid.scss file in your project's SCSS:
```sh
@import 'path/to/_grid.scss';
```

4. Apply grid classes to your HTML elements:
```sh
<section class="grid-test">
  <div class="row">
    <div class="col-1-of-2">
      Col 1 of 2
    </div>
    <div class="col-1-of-2">
      Col 1 of 2
    </div>
  </div>
  <!-- Add more rows and columns as needed -->
</section>
```
## Column Sizes

You can use the following classes for different column sizes:

- `.col-1-of-2`: 50% width
- `.col-1-of-3`: 33.33% width
- `.col-1-of-4`: 25% width
- `.col-2-of-3`: 66.66% width
- `.col-2-of-4`: 50% width
- `.col-3-of-4`: 75% width
Make sure to calculate the column width as shown in the code for accurate sizing.

## Codepen

https://codepen.io/gianniszisakis/pen/xxmobvz

