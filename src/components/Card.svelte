<script>
    import Comment from "./Comment.svelte";
</script>

<div class="Card">
    <div class="Card-container">
        <div class="Card-header">
            <div class="Card-user">
                <img src="https://arepa.s3.amazonaws.com/elmo002.jpg" alt="">
                <h2>
                    Elmo.pug
                    <span>Bogotá, Colombia</span>
                </h2>
            </div>
            <div class="Card-settings">
                <i class="fa-solid fa-ellipsis-vertical"></i>
            </div>
        </div>
        <div class="Card-photo">
            <figure>
                <img src="https://arepa.s3.amazonaws.com/elmo002.jpg" alt="">
            </figure>
        </div>
        <div class="Card-icons">
            <div class="Card-icons-first">
                <i class="fa-brands fa-gratipay"></i>
                <i class="fa-solid fa-share"></i>
            </div>
            <div class="Car-icons-second">
                <i class="fa-solid fa-bookmark"></i>
            </div>
            <div class="Card-description">
                <h3>elmo.pgu</h3>
                <span>Hola!</span>
            </div>
            <Comment></Comment>
        </div>
    </div>
</div>