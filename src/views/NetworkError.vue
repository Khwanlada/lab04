<template>
    <div class="networkError">
        <h1>Uh-Oh!</h1>

        <h3>
            It looks like you're experiencing some issue, please take a breath and 
            <a href="#" @click="$router.go(-1)">click here</a> to try again.
        </h3>
    </div>
</template>