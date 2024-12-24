<template>
  <Header />
  <main>
    <article>
      <section class="">
        <div class="container-fluid">
          <div class="main-wrapper">
            <Sidebar />
            <div class="content-frame">
              <div class="playlist-listing">
                <div class="playlist-section">
                  <div class="playlist-top-actions">
                    <h2 class="section-heading"><a href="#">Popular Artists</a></h2>
                    <a href="#" class="show-all">Show all</a>
                  </div>

                  <Artist />
                </div>
                <div class="playlist-section">
                  <div class="playlist-top-actions">
                    <h2 class="section-heading"><a href="#">Popular albums and singers</a></h2>
                    <a href="#" class="show-all">Show all</a>
                  </div>

                  <Albums />
                </div>
                <div class="playlist-section">
                  <div class="playlist-top-actions">
                    <h2 class="section-heading"><a href="#">Popular Radio</a></h2>
                    <a href="#" class="show-all">Show all</a>
                  </div>
                  <Radio />
                </div>
                <div class="playlist-section">
                  <div class="playlist-top-actions">
                    <h2 class="section-heading"><a href="#">Feature charts</a></h2>
                    <a href="#" class="show-all">Show all</a>
                  </div>
                  <ChartsPlaylist />
                </div>
                <div class="playlist-section">
                  <div class="playlist-top-actions">
                    <h2 class="section-heading"><a href="#">Playlist of our editors</a></h2>
                    <a href="#" class="show-all">Show all</a>
                  </div>
                  <EditorsPlaylist />
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </article>
  </main>
</template>

<script setup lang="ts">
import Header from '@/components/Header.vue'
import Sidebar from '@/components/Sidebar.vue'
import Artist from '@/components/Artist.vue'
import Albums from '@/components/Albums.vue'
import Radio from '@/components/Radio.vue'
import ChartsPlaylist from '@/components/ChartsPlaylist.vue'
import EditorsPlaylist from '@/components/EditorsPlaylist.vue'
</script>
