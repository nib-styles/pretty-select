# select

Styles for a `<select>` written in pure HTML/JS so it can be styled nicely - unlike native ones. 

## Usage

    <div class="select js-select">
        <div class="select__input"></div>
        <div class="select__menu menu">
            <div class="menu__item" data-value="avoid-tax">Cover to avoid tax</div>
            <div class="menu__item" data-value="cheaper-cover">Something cheaper</div>
            <div class="menu__item" data-value="health-concern">A specific health concern</div>
            <div class="menu__item" data-value="better-cover">Looking for better cover</div>
            <div class="menu__item" data-value="compare-cover">Just want to compare</div>
        </div>
    </div>

## Building

    $ npm run build

**Note:** Requires SASS 3.3 to build
