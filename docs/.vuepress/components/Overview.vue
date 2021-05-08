<template>
  <div class="overview-row">
    <div class="category">
      <h2>Properties</h2>
      <a href="/documentation/properties.html#absolute-relative-layout">Absolute/Relative Layout</a>
      <a href="/documentation/properties.html#align-content">Align Content</a>
      <a href="/documentation/properties.html#align-items">Align Items</a>
      <a href="/documentation/properties.html#align-self">Align Self</a>
      <a href="/documentation/properties.html#aspect-ratio">Aspect Ratio</a>
      <a href="/documentation/properties.html#flex-direction">Flex Direction</a>
      <a href="/documentation/properties.html#flex-wrap">Flex Wrap</a>
      <a href="/documentation/properties.html#flex-basis-grow-and-shrink">Flex Basis, Grow, and Shrink</a>
      <a href="/documentation/properties.html#justify-content">Justify Content</a>
      <a href="/documentation/properties.html#layout-direction">Layout Direction</a>
      <a href="/documentation/properties.html#margins-paddings-and-borders">Margins, Paddings, and Borders</a>
      <a href="/documentation/properties.html#max-min-width-and-height">Max / Min Width and Height</a>
      <a href="/documentation/properties.html#width-and-height">Width and Height</a></div>
    <div class="category">
      <h2>Examples</h2>
      <a class='disabled' href="javascript:void(0) ">Flexible Text</a>
      <a class='disabled' href="javascript:void(0) ">Floating Buttons</a>
      <a class='disabled' href="javascript:void(0) ">Overlays</a>
    </div>
    <div class="category">
      <h2>Contributing</h2>
      <a class='disabled' href="javascript:void(0) ">Opening a Pull Request</a>
      <a class='disabled' href="javascript:void(0) ">Testing</a>
      <a class='disabled' href="javascript:void(0) ">Writing Documentation</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Overview"
}
</script>

<style lang="less">
  .overview-row {
    width: auto;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    flex-wrap: wrap;
    .category {
      display: flex;
      flex-direction: column;
      margin: 1rem 0;
      h2 {
        font-size: 16px;
        font-weight: 700;
      }
      a {
        font-size: 16px;
        font-weight: 500;
        line-height: 250%;
        color: #74a9ff;
        &.disabled{
          &:hover {
            text-decoration: none;
            cursor: default;
          }
          color: #dcdfe6;
        }
      }
    }
  }
</style>