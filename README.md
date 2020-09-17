![css-to-scss logo](https://raw.githubusercontent.com/Firebrand/teagrid/master/logo2.png)

# TeaGrid
A tiny but powerful css grid framework. Emulates most of Bootstrap's grid in just a couple lines of SCSS code!

**tea.scss** is the only file you need.

### TeaGrid advantages over Bootstrap Grid
- Much smaller footprint
- Better namespaced
- Easier to customize gutter widths, margins etc.

### TeaGrid classes and their Bootstrap equivalents

| Bootstrap | TeaGrid |
| ------ | ------ |
| container | tea-container |
| row | tea-row |
| col | tea-col |
| col-[number of cols to span] (ex. **col-6**) | tea-col[number of cols to span] (ex. **tea-col6**) |
| col-[number of cols to span]-[apply to this breakpoint and above] (ex. **col-6-md**) | tea-col[number of cols to span]-[apply to this breakpoint and above] (ex. **tea-col6-md**)|

### Further documentation

The /test folder contains the Bootstrap 4.2 documentation for their grid, but under each example you'll find the TeaGrid version as well.
This is used for both documentation and testing purposes.
