<script>
  export let segment;
</script>

<style>
  @import url("https://fonts.googleapis.com/css?family=Ubuntu&display=swap");
  nav {
    border-bottom: 1px solid rgba(255, 62, 0, 0.1);
    font-weight: 300;
    padding: 0 1em;
    display: grid;
    grid-template-columns: repeat(2, 50%);
    align-items: center;
  }

  ul {
    margin: 0;
    padding: 0;
  }

  /* clearfix */
  ul::after {
    content: "";
    display: block;
    clear: both;
  }

  li {
    display: block;
    float: right;
    text-align: right;
  }

  .selected {
    position: relative;
    display: inline-block;
  }

  .selected::after {
    position: absolute;
    content: "";
    width: calc(100% - 1em);
    height: 2px;
    background-color: rgb(0, 0, 0);
    display: block;
    bottom: -1px;
  }

  a {
    text-decoration: none;
    padding: 1em 0.5em;
    display: block;
  }
  .menu-items {
    text-align: right;
  }
</style>

<nav>
  <div>
   <a class={segment === undefined} href=".">
   <svg
      xmlns="http://www.w3.org/2000/svg"
      xmlns:xlink="http://www.w3.org/1999/xlink"
      style="isolation:isolate"
      viewBox="185.375 149.841 76.625 15.694"
      width="76.625pt"
      height="15.694pt">
      <defs>
        <clipPath id="_clipPath_B7dVjRj8HdGs7yxqpLM8qdAvx6XYJJgV">
          <rect x="185.375" y="149.841" width="76.625" height="15.694" />
        </clipPath>
      </defs>
      <g clip-path="url(#_clipPath_B7dVjRj8HdGs7yxqpLM8qdAvx6XYJJgV)">
        <text
          transform="matrix(1,0,0,1,200,162.889)"
          style="font-family:'Ubuntu';font-weight:400;font-size:14px;font-style:normal;fill:#4f4f4f;stroke:none;">
          learnweb
        </text>
        <g>
          <g>
            <g>
              <g>
                <path
                  d=" M 190.688 152.375 C 193.663 152.375 196 154.712 196
                  157.688 C 196 160.663 193.663 163 190.688 163 C 187.712 163
                  185.375 160.663 185.375 157.688 C 185.375 154.712 187.712
                  152.375 190.688 152.375 Z M 190.688 153.969 C 188.671 153.969
                  186.969 155.671 186.969 157.688 C 186.969 159.704 188.671
                  161.406 190.688 161.406 C 192.704 161.406 194.406 159.704
                  194.406 157.688 C 194.406 157.265 194.315 156.848 194.207
                  156.425 C 193.888 156.849 193.344 157.156 192.813 157.156 C
                  191.962 157.156 191.219 156.413 191.219 155.563 C 191.219
                  155.031 191.527 154.487 191.95 154.167 C 191.526 154.06 191.11
                  153.969 190.688 153.969 Z "
                  fill="rgb(74,134,0)" />
              </g>
            </g>
          </g>
        </g>
      </g>
    </svg>
   
   </a>
    
  </div>
  <div class="menu-items">
    <ul>
      <li>
        <a class={segment === 'Github' ? 'selected' : ''} href="https://github.com/learnwebleif/learnweb"><img width="20px" src="github.svg" alt="Github"></a>
      </li>
      <li>
        <a class={segment === 'kontakt' ? 'selected' : ''} href="contact">kontakt</a>
      </li>

      <!-- for the blog link, we're using rel=prefetch so that Sapper prefetches
		     the blog data when we hover over the link or tap it on a touchscreen -->
      <!-- <li>
        <a
          rel="prefetch"
          class={segment === 'blog' ? 'selected' : ''}
          href="blog">
          blogg
        </a>
      </li> -->
    </ul>
  </div>
</nav>
