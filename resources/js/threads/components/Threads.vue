<template>
    <div class="card">
        <div class="card-content">
            <span class="card-title">{{ title }}</span>

            <table>
                <thead>
                    <tr>
                        <th>#</th>
                        <th>{{ threads }}</th>
                        <th>{{ replies }}</th>
                        <th></th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1</td>
                        <td>Topic nice bla bla bla bla bla</td>
                        <td>3</td>
                        <td>
                            <a href="/threads/1">{{ open }}</a>
                        </td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</template>

<script>
    export default {
        props: [
            'title',
            'threads',
            'replies',
            'open'
        ]
    }
</script>
