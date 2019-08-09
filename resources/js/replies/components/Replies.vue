<template>
    <div>
        <div class="card">
            <div class="card-content">
                <span class="card-title">Armando {{ relied }}</span>
                <blockquote>
                    Inventore provident id rem animi molestiae facere. Magni ex molestiae repellendus fuga. Beatae est impedit sunt autem non deleniti.
                </blockquote>
            </div>
        </div>
        <div class="card">
            <div class="card-content">
                <span class="card-title">Armando {{ relied }}</span>
                <blockquote>
                    Inventore provident id rem animi molestiae facere. Magni ex molestiae repellendus fuga. Beatae est impedit sunt autem non deleniti.
                </blockquote>
            </div>
        </div>
        <div class="card">
            <div class="card-content">
                <span class="card-title">Armando {{ relied }}</span>
                <blockquote>
                    Inventore provident id rem animi molestiae facere. Magni ex molestiae repellendus fuga. Beatae est impedit sunt autem non deleniti.
                </blockquote>
            </div>
        </div>
        <div class="card grey lighten-4">
            <div class="card-content">
                <span class="card-title">{{ reply }}</span>

                <form action="">
                    <div class="input-field">
                        <textarea class="materialize-textarea" rows="10" :placeholder="yourAnswer"></textarea>
                        <button type="submit" class="btn red accent-12">{{ send }}</button>
                    </div>
                </form>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        props: [
            'send',
            'reply',
            'yourAnswer',
            'replied'
        ]
    }
</script>
