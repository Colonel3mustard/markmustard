<template>
    <v-container fluid class="page">
        <v-card class="card">
            <v-card-title>Skills</v-card-title>
            <v-card-subtitle>Languages and Frameworks</v-card-subtitle>
            <ul class="list">
                <li class="listItem">Javascript</li>
                <li class="listItem">Vue.js</li>
                <li class="listItem">Node.js</li>
                <li class="listItem">C#/.NET</li>
                <li class="listItem">GraphQL</li>
                <li class="listItem">SQL</li>
                <li class="listItem">HTML</li>
                <li class="listItem">CSS</li>
            </ul>
        </v-card>
        <v-card class="card">
            <v-card-title>Tools</v-card-title>
            <v-card-subtitle>Software</v-card-subtitle>
            <ul class="list">
                <li class="listItem">Visual Studio Code</li>
                <li class="listItem">Visual Studio</li>
                <li class="listItem">Prisma</li>
                <li class="listItem">Postgres</li>
                <li class="listItem">MSSMS</li>
                <li class="listItem">Postman</li>
                <li class="listItem">Swagger</li>
            </ul>
        </v-card>
        <v-card class="card">
            <v-card-title>Proficiencies</v-card-title>
            <v-card-subtitle>Industry Knowledge</v-card-subtitle>
            <ul class="list">
                <li class="listItem">Object Oriented Programming (OOP)</li>
                <li class="listItem">Test Driven Development</li>
                <li class="listItem">Web Development</li>
                <li class="listItem">Agile Methodologies</li>
                <li class="listItem">Database Design</li>
            </ul>
        </v-card>
    </v-container>
</template>

<style scoped>
.icon{
    max-height: 50px;
}
.list{
    padding-left: 10%;
    padding-bottom: 2%;
    
}
.listItem{
    font-size: 0.5em
}
.card{
    margin-bottom: 2%;
}
</style>