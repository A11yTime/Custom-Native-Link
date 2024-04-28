<template>
    <div class="custom-shade">
        <h1>Custom Link</h1>
        <div>
        <div class="custom-link" tabindex="0" @keyup="linktarget" onclick="location.href='https://www.williams-sonoma.com/'">I'm Custom</div>
    </div>
    </div>
</template>
<style scoped>
   .custom-shade {
    background-color: lightgray;
    padding: 5px;
    margin: 10px;
}
  .custom-link {
    display: inline-block;
    padding: 8px 16px;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    border-radius: 4px;
    transition: background-color 0.3s ease;
    outline-offset: 2px;
}

.custom-link:hover {
    background-color: #0056b3;
    cursor: pointer;
}
</style>
