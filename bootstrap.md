## Bootstrap notes 

- `jQuery` required for JS widgets 

### Classes 
Examples 
- `container` - adds responsive padding 
- `container-fluid` maintains distance from aligned rule despite screen resizing 
- `page-header` - styles font and adds rule 
- `lead` - emphasizes section of paragraph

Alignment 
- `text-left` - left aligned text 
- `text-center` - center aligned text 
- `text-right` - right aligned text 
- `text-justify` - jusitified text 
- `text-nowrap` - no wrap text 

Transformation 
- `text-lowercase`
- `text-uppercase`
- `text-capitalize`
- `blockquote`
- `blockquote-reverse` - right align 

Quick float 
- `pull-right` - floats right 
- `pull-left` - floats left 
- `clearfix`

List 
- `list-unstyled`
- `list-inline`
- `list-group`
- Item styling 
    - `list-group-item`
    - Can add a default `active` class to `<a>` tags used in menus 
    - Contextual colors 

Contextual colors 
- `text-primary` - blue-gray
- `text-success` - green 
- `text-info` - light blue
- `text-warning` - yellow
- `text-danger` - red 
- `text-muted` - light gray 

Contextual backgrounds 
- Same as colors, just exchanging `text` for `bg`

Buttons 
- `btn`
- Stylings 
    - `btn-default`
        - Can style links and inputs, but good idea to include `role="button'`
    - `btn-primary`
    - `btn-success` 
    - `btn-info`
    - `btn-warning`
    - `btn-danger`
    - `btn-link`
- Sizes 
    - `btn-lg`
    - `btn-sm` 
    - `btn-xs`

Forms 
- Wrap labels and input fields in `form-group` divs
- `form-control`
- `help-block` 
    - e.g. `<input type="file"><p class="help-block">Only png and jpg allowed</p>
- `checkbox` 
- `form-inline` 

Tables 
- `table`
- Styling 
    - `table-striped`
    - `table-bordered`
    - `table-hover`
    - `table-condensed`
    - Rows accept contextual styling 

Panels 
- `panel`
- `panel-heading`
- `panel-body` 
- `panel-footer`
- Styling accepts contextual colors 

Wells 
- `well`
- `well-lg`
- `well-sm`

Alerts 
- `alert` 
- Styling accepts contextual colors 
- `alert-dismissible`
    - Contain a button with `class="close"` and `data-dismiss="alert"`
    - Requires JS file linked

Progress bars 
- `progress` wrapper 
- `progress-bar` 
    - `style="width:50%;"`
    - Accepts contextual colors 
    - `progess-bar-striped`
    - `active` - animates 

Labels 
- `label` 
- Accepts contextual colors 
- Contain within header tags for sizing 

Badges 
- e.g. `Messages <span class="badge">2</span>`

Images 
- `thumbnail`
- `img-rounded`
- `img-circle`

Grids 
- `row`
```HTML
<div class="row">
    <div class="col-md-8"></div>
    <div class="col-md-4"></div>
</div>
```
- Divides row into 8 and 4 parts 
- `md` stands for medium screen size 
- `col-sm-` and `col-xs-` sets columns for smaller screens (like media query)

Navbar 
- `navbar`
- Code found in documentation 
- JS required for dropdowns to work 
- `navbar-inverse` inverts colors 

Jumbotron 
- `jumbotron`


### Tags 
- `<small>` - shrinks and fades text 
- `<mark>`
- `<del>`
- `<u>`
- `<blockquote>`
    - Add `<footer>` with author in `<cite>` tags 
- `<code>&lt;h1&gt;Heading Text&lt;/h1&gt;</code>`
- `<kbd>`

#### Sources
- [Bootstrap Beginner Crash Course - Traversy Media](https://www.youtube.com/watch?v=5GcQtLDGXy8)