<template>
  <div class="albums-listing">
    <ul>
      <!-- loop to be added to render data -->
      <li v-for="i in 7" :key="i">
        <div class="album-item">
          <div class="album-item-inner">
            <div class="album-image">
              <a href="#">
                <figure>
                  <img :src="sample2" class="img-fluid" alt="" />
                </figure>
                <span class="play-icon">
                  <svg
                    data-encore-id="icon"
                    role="img"
                    aria-hidden="true"
                    viewBox="0 0 24 24"
                    class="Svg-sc-ytk21e-0 bneLcE"
                  >
                    <path
                      d="m7.05 3.606 13.49 7.788a.7.7 0 0 1 0 1.212L7.05 20.394A.7.7 0 0 1 6 19.788V4.212a.7.7 0 0 1 1.05-.606z"
                    ></path>
                  </svg>
                </span>
              </a>
            </div>
            <div class="album-content">
              <p><a href="#">With Sachin-Jigar, Vishal-Shekhar, Amit Trivedi and more </a></p>
            </div>
          </div>
        </div>
      </li>
    </ul>
  </div>
</template>

<script setup lang="ts">
import sample2 from '@/assets/images/editors.jpeg'
</script>
