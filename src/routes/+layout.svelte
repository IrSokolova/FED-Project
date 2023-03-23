<script lang="ts">
    import {base} from "$app/paths";
</script>

<header class="lay-h">
    <a href='{base}/'> Home </a>
</header>
<slot />
<footer class="foot-h">
    <a href='https://www.youtube.com/watch?v=j5a0jTc9S10&list=PLNTK9welGzDynukDlMqLGqY3rlaMPOJOl&index=10'> Cute Little Puppy Doing Cute things </a>
</footer>
<style>
    .lay-h {
        background-color: antiquewhite;
        text-align: center;
        color: blueviolet;
        margin-left: 20px;
    }

    .foot-h {
        background-color: antiquewhite;
        text-align: center;
        color: blueviolet;
        margin-left: 20px;
    }
</style>