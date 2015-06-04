# select

Theme for select component

## Usage

    <div class="selectbox js-select">
        <div class="selectbox__selected js-selected"></div>
        <div class="selectbox__menu js-menu">
            <div class="selectbox__option" data-value="avoid-tax">Cover to avoid tax</div>
            <div class="selectbox__option" data-value="cheaper-cover">Something cheaper</div>
            <div class="selectbox__option" data-value="health-concern">A specific health concern</div>
            <div class="selectbox__option" data-value="better-cover">Looking for better cover</div>
            <div class="selectbox__option" data-value="compare-cover">Just want to compare</div>
        </div>
    </div>

## Building

    $ sass index.scss > index.css
    $ component build --dev

**Note:** Requires SASS 3.3 to build
