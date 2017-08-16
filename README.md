# iOS-style Components
Just some CSS experiments with iOS style UI components.

### iOS Toggle
Built entirely using SCSS; you can customise the dimensions of the toggle using the original SCSS file and compiling it yourself, or you can include the `ios-toggle.css` and use the standard dimensions.  
All you need to do is apply the class `ios-toggle` to the input (checkbox supported currently), and place a label *after* it. The toggle is right-aligned inside the container element.

#### To be implemented
- Check toggle against iOS screenshots (colours, sizes)
- Compiled version supporting small, regular and large toggles
- Compiled version supporting `em` units

**Current usage:**
```
<input type="checkbox" id="ios-checkbox" class="ios-toggle" />
<label for="ios-checkbox">iOS-style Checkbox</label>
```
