<div>
  <li>
    <div class="split">
      <div class="left">
        <slot name="left" />
      </div>
      <div class="right">
        <div class="img">
          <slot name="right" />
        </div>
      </div>
    </div>
  </li>
  <hr />
</div>

<style lang="scss">
  .split {
    display: flex;
    flex-direction: row;
    justify-content: space-between;

    .left {
      text-align: left;
      width: 50em;
      margin-bottom: auto;
      margin-top: auto;
    }

    .right {
      margin: auto;
      .img {
        margin: auto;
        width: 20vw;
        // height: 50%;
      }
    }
  }

  hr {
    border-top: 1px solid lightgray;
    width: 97%;
    margin-left: 0;
  }
</style>
