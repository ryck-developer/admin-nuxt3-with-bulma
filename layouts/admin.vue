<template>
  <div>
    <div class="aviso">O sorriso é a melhor roupa que você pode vestir.</div>
    <nav class="navbar">
      <div class="navbar-brand">
        <a href="/" class="navbar-item"
          ><img
            src="http://bulma.io/images/bulma-logo.png"
            alt="Bulma: a modern CSS framework based on Flexbox"
            width="112"
            height="28"
        /></a>
        <a href="#" target="_blank" class="navbar-item is-hidden-desktop"
          ><span class="icon" style="color: #333"
            ><i class="fa fa-github"></i></span
        ></a>
        <a href="#" target="_blank" class="navbar-item is-hidden-desktop"
          ><span class="icon" style="color: #55acee"
            ><i class="fa fa-twitter"></i></span
        ></a>
        <div data-target="navMenubd-example" class="navbar-burger burger">
          <span></span> <span></span> <span></span>
        </div>
      </div>
      <div id="navMenubd-example" class="navbar-menu">
        <div class="navbar-start">
          <div class="navbar-item has-dropdown is-hoverable">
            <a
              href="/documentation/overview/start/"
              class="navbar-link is-active"
            >
              Docs
            </a>
            <div class="navbar-dropdown">
              <a href="/documentation/overview/start/" class="navbar-item">
                Overview
              </a>
              <a href="/" class="navbar-item"> Modifiers </a>
              <a
                href="http://bulma.io/documentation/columns/basics/"
                class="navbar-item"
              >
                Columns
              </a>
              <a
                href="http://bulma.io/documentation/layout/container/"
                class="navbar-item"
              >
                Layout
              </a>
              <a
                href="http://bulma.io/documentation/form/general/"
                class="navbar-item"
              >
                Form
              </a>
              <a
                href="http://bulma.io/documentation/elements/box/"
                class="navbar-item"
              >
                Elements
              </a>
              <a
                href="http://bulma.io/documentation/components/breadcrumb/"
                class="navbar-item is-active"
              >
                Components
              </a>
              <hr class="navbar-divider" />
              <div class="navbar-item">
                <div>
                  <p class="is-size-6-desktop">
                    <strong class="has-text-info">0.5.1</strong>
                  </p>
                  <small
                    ><a href="/versions" class="bd-view-all-versions"
                      >View all versions</a
                    ></small
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="navbar-item has-dropdown is-hoverable">
            <a href="http://bulma.io/blog/" class="navbar-link"> Blog </a>
            <div
              id="blogDropdown"
              data-style="width: 18rem;"
              class="navbar-dropdown"
            >
              <a href="/2017/08/03/list-of-tags/" class="navbar-item">
                <div class="navbar-content">
                  <p><small class="has-text-info">03 Aug 2017</small></p>
                  <p>New feature: list of tags</p>
                </div>
              </a>
              <a
                href="/2017/08/01/bulma-bootstrap-comparison/"
                class="navbar-item"
              >
                <div class="navbar-content">
                  <p><small class="has-text-info">01 Aug 2017</small></p>
                  <p>Bulma / Bootstrap comparison</p>
                </div>
              </a>
              <a
                href="/2017/07/24/access-previous-bulma-versions/"
                class="navbar-item"
              >
                <div class="navbar-content">
                  <p><small class="has-text-info">24 Jul 2017</small></p>
                  <p>Access previous Bulma versions</p>
                </div>
              </a>
              <a href="http://bulma.io/blog/" class="navbar-item">
                More posts
              </a>
              <hr class="navbar-divider" />
              <div class="navbar-item">
                <div class="navbar-content">
                  <div class="level is-mobile">
                    <div class="level-left">
                      <div class="level-item">
                        <strong>Stay up to date!</strong>
                      </div>
                    </div>
                    <div class="level-right">
                      <div class="level-item">
                        <a
                          href="http://bulma.io/atom.xml"
                          class="button bd-is-rss is-small"
                          ><span class="icon is-small"
                            ><i class="fa fa-rss"></i
                          ></span>
                          <span>Subscribe</span></a
                        >
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="navbar-item has-dropdown is-hoverable">
            <div class="navbar-link">More</div>
            <div id="moreDropdown" class="navbar-dropdown">
              <a href="http://bulma.io/extensions/" class="navbar-item">
                <div class="level is-mobile">
                  <div class="level-left">
                    <div class="level-item">
                      <p>
                        <strong>Extensions</strong> <br />
                        <small>Side projects to enhance Bulma</small>
                      </p>
                    </div>
                  </div>
                  <div class="level-right">
                    <div class="level-item">
                      <span class="icon has-text-info"
                        ><i class="fa fa-plug"></i
                      ></span>
                    </div>
                  </div>
                </div>
              </a>
            </div>
          </div>
          <a href="http://bulma.io/expo/" class="navbar-item"
            ><span class="bd-emoji">🎨</span>
            Expo
          </a>
          <a href="http://bulma.io/love/" class="navbar-item"
            ><span class="bd-emoji">❤️</span>
            Love
          </a>
        </div>
        <div class="navbar-end">
          <a
            href="https://github.com/jgthms/bulma"
            target="_blank"
            class="navbar-item is-hidden-desktop-only"
            ><span class="icon" style="color: #333"
              ><i class="fa fa-github"></i></span
          ></a>
          <a
            href="https://twitter.com/jgthms"
            target="_blank"
            class="navbar-item is-hidden-desktop-only"
            ><span class="icon" style="color: #55acee"
              ><i class="fa fa-twitter"></i></span
          ></a>
          <div class="navbar-item">
            <div class="field is-grouped">
              <p class="control">
                <a
                  data-social-network="Twitter"
                  data-social-action="tweet"
                  data-social-target="http://bulma.io"
                  target="_blank"
                  href="https://twitter.com/intent/tweet?text=Bulma: a modern CSS framework based on Flexbox&amp;hashtags=bulmaio&amp;url=http://bulma.io&amp;via=jgthms"
                  class="bd-tw-button button"
                  ><span class="icon"><i class="fa fa-twitter"></i></span>
                  <span> Tweet </span></a
                >
              </p>
              <p class="control">
                <a
                  href="https://github.com/jgthms/bulma/archive/0.5.1.zip"
                  class="button is-primary"
                  ><span class="icon"><i class="fa fa-download"></i></span>
                  <span>Download</span></a
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </nav>

    <div class="container">
      <Nuxt />
    </div>
  </div>
</template>

<style>
.aviso {
  padding: 5px;
  background: #f9a7b0;
  text-align: center;
  color: white;
}
</style>
