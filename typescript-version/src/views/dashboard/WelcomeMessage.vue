<script setup lang="ts"></script>

<template>
  <!-- 以下のメッセージを表示
    自分のセッティングを把握、共有しよう
    Gsettingsは旧Gsettingsから生まれ変わり、従来の振り向き計算機能も保持しつつ、
    現在メインでプレイしているゲームや、使用しているデバイスの登録・共有する機能も追加しました。 -->
  <v-card class="mb-2">
    <v-card-text>
      <v-row>
        <v-col cols="12">
          <v-img
            src="{trophy}"
            alt="trophy"
            class="trophy"
          />
          <h4 class="mb-1">自分のセッティングを把握、共有しよう</h4>
          <p class="mb-0">Gsettingsは旧Gsettingsから生まれ変わり、従来の振り向き計算機能も保持しつつ、</p>
          <p class="mb-0">
            現在メインでプレイしているゲームや、使用しているデバイスの登録・共有する機能も追加しました。
          </p>
          <p class="mb-0">振り向き計算機能は従来通りログインなしで使用可能です。<br /></p>
        </v-col>
      </v-row>
    </v-card-text>
  </v-card>
</template>

<style lang="scss">
.v-card .trophy {
  position: absolute;
  inline-size: 5.188rem;
  inset-block-end: 1.25rem;
  inset-inline-end: 1.25rem;
}
</style>
