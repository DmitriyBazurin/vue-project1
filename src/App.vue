<template>
    <div>
        <div class="post">
            <div><strong>Название:</strong> Пост о js</div>
            <div><strong>Описание:</strong> Текст с описанием на сайте</div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            likes: 0,
            dislikes: 0,
        }
    },
    methods: {
        addLike() {
            this.likes +=1;
        },
        addDislike() {
            this.dislikes +=1;
        }
    }
}
</script>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.post {
    margin: 15px;
    padding: 15px;
    border: 2px solid teal;
}
</style>

