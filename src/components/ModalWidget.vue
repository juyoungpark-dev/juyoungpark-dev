<template>
  <!-- Modal -->
  <div
    class="modal fade"
    id="myModal"
    tabindex="-1"
    role="dialog"
    aria-labelledby="myModalLabel"
    aria-hidden="true"
  >
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <button
            type="button"
            class="close"
            data-dismiss="modal"
            aria-hidden="true"
          >
            &times;
          </button>
          <h4 class="modal-title" id="myModalLabel">Projects</h4>
        </div>
        <div class="modal-body">Coming Soon...</div>
        <div class="modal-footer">
          <button
            type="button"
            class="btn btn-default btn-simple"
            data-dismiss="modal"
          >
            Close
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "ModalWidget",
  setup() {},
});
</script>
