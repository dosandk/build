this folder keep sylesheets with placeholder-selectors like %foo

%foo {
    color: blue;
    font-weight: bold;
    font-size: 2em;
}

.bar {
    @extend %foo;
}

Is compiled to:

.bar {
    color: blue;
    font-weight: bold;
    font-size: 2em;
}