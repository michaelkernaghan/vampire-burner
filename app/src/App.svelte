<script lang="ts">
</script>

<main>
  <header class="ScriptHeader">
    <div class="rt-container">
      <div class="col-rt-12">
        <div class="rt-heading">
          <div class="title">Vampire Tokens</div>
        </div>
        <img src={`images/vampire.png`} alt={"vampire"} style="width:80px" />
      </div>
    </div>
  </header>
  <section>
    <div class="rt-container">
      <div class="col-rt-12">
        <div class="Scriptcontent">
          <div class="container">
            <div class="package-container">
              <div class="packages">
                <h1>Hunt</h1>
                <ul class="list">
                  <li class="first">The vampires are on the loose!</li>
                  <li>
                    Vampires sleep during the day but can be roused from their
                    coffins if you swap Tez with them
                  </li>
                </ul>
                <a href="#" class="button button1"
                  ><a
                    href="https://quipuswap.com/swap?from=tez&to=KT1QQPYLhqHSkJQNYdLQuNAw5uYkQbJ1s2Jw_0"
                    >Swap V</a
                  ></a
                >
              </div>
              <div class="packages">
                <h1>Stake</h1>
                <ul class="list">
                  <li class="first">
                    Stake vampires by adding to the liquidity pool
                  </li>
                  <li>Earn rewards</li>
                  <li>You can unstake a vampire at anytime but lookout!</li>
                </ul>
                <a href="#" class="button button2"
                  ><a
                    href="https://quipuswap.com/invest/add-liquidity/KT1QQPYLhqHSkJQNYdLQuNAw5uYkQbJ1s2Jw_0"
                    >Add V Liquidity</a
                  ></a
                >
              </div>
              <div class="packages">
                <h1>Burn</h1>
                <ul class="list">
                  <li class="first">
                    Burn vampires by sending them to
                    <p class="smaller">KT1CZMurPAjSfZqcn6LBUNUhG4byE6AJgDT6</p>
                  </li>
                  <li>Vampires burn when exposed to sunlight</li>
                </ul>

                <a href="#" class="button button3">
                  <a
                    href="https://tzkt.io/KT1CZMurPAjSfZqcn6LBUNUhG4byE6AJgDT6/operations/"
                    >Burn V</a
                  ></a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</main>

<style lang="scss">
  $blood-red: #880808;

  

  .title {
  color: $blood-red;
  font-family:   Helvetica, sans-serif;
  font-size: 100px;
  margin: 20px;
}

  .container {
    width: 100%;
  }

  .packages {
    margin: 20px;
    width: 300px;
    padding-bottom: 1.5em;
    height: 100%;
    background-color: $blood-red;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    border-radius: 20px;
    box-shadow: 0 19px 38px rgba(30, 35, 33, 1),
      0 15px 12px rgba(30, 35, 33, 0.2);
    flex-wrap: wrap;
    color: #f4f4f4;
    font-family:   Helvetica, sans-serif;
  }

  h1,
  h2 {
    font-size: 2.2em;
  }
  .text1,
  .text2 {
    color: #fff;
  }

  .list li {
    font-size: 18px;
    list-style: none;
    border-bottom: 1px solid #f4f4f4;
    padding-inline-start: 0;
    border-width: 1px;
    padding: 10px;
    font-family:   Helvetica, sans-serif;
  }

  .smaller {
    font-size: 12px;
    font-family:   Helvetica, sans-serif;
    text-align: center;
  }

  .first {
    margin-top: 40px;
    border-top: 1px solid #f4f4f4;
  }

  .list {
    width: 80%;
  }

  ul {
    padding: 0;
  }

 .button {
    padding: 10px 30px;
    text-decoration: none;
    font-size: 1.4em;
    margin: 15px 15px;
    border-radius: 50px;
    color: #f4f4f4;
    transition: all 0.3s ease 0s;
    font-family:   Helvetica, sans-serif;
  }

  .button:hover {
    transform: scale(1.2);
  }

  .button1 {
    background-color: #00cc99;
    box-shadow: 0 0 10px 0 #00cc99 inset, 0 0 20px 2px #00cc99;
  }

  .button2 {
    background-color: #0faae7;
    box-shadow: 0 0 10px 0 #0faae7 inset, 0 0 20px 2px #0faae7;
  }

  .button3 {
    background-color: #ffae42;
    box-shadow: 0 0 10px 0 #ffae42 inset, 0 0 20px 2px #ffae42;
  }

  .package-container {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
  }
</style>
