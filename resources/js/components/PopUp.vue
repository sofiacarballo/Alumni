<template>
    <div class="modal fade" :id="popUpId">
      <div class="modal-dialog">
        <div class="modal-content card-alumni-s">
          <div class="modal-body">
            <slot></slot>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
  export default {
        props: ['popUpId']
    }
</script>
