<template>
  <div class="mcw-demo mcw-demo--fluid">
    <mcw-layout-grid class="my-grid">
      <mcw-layout-cell class="cell cell1" desktop="3" tablet="3"/>
      <mcw-layout-cell class="cell cell2" desktop="3" tablet="5" align="top">
        <mcw-body1>align="top"</mcw-body1>
      </mcw-layout-cell>
      <mcw-layout-cell class="cell cell3" desktop="3" tablet="5" align="middle">
        <mcw-body1>align="middle"</mcw-body1>
      </mcw-layout-cell>
      <mcw-layout-cell class="cell cell4" desktop="3" tablet="3" align="bottom">
        <mcw-body1>align="bottom"</mcw-body1>
      </mcw-layout-cell>
    </mcw-layout-grid>
  </div>
</template>

<style>
.mcw-demo .cell {
  border: 1px dashed;
  min-height: 50px;
  text-align: center;
  padding-top: 4px;
}

.mcw-demo .cell.cell1 {
  min-height: 100px;
}

.mcw-demo .cell.cell4 {
  min-height: 80px;
}
</style>
