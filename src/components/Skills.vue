<template>
  <div class="page">
    <v-row fluid>
      <v-col class="col" fluid>
      <v-card >
      <v-card-title>Summary</v-card-title>
      <v-card-subtitle>About me</v-card-subtitle>
      <v-card-text>
        As a Software Developer with a background in Management and Sales,
         I am constantly driven by a passion for mastering new things. 
         I have taught myself everything from guitar, 
         to advanced Microsoft Excel to track employee efficiency 
         in my former job. Coming from that background in sales 
         and warehouse environments, 
         I was drawn to programming 
         as there is always something new to learn. 
         After graduating from Tech Elevator Coding Bootcamp 
         in August of 2019 I joined Ingage Parters, 
         whom I consult for at GE Aviation
         in downtown Cincinnati. I currently do a mix of automated QA
         and Front End Development there, and I'm excited to move into
         development full-time in the near future.
         </v-card-text>
      </v-card>
      </v-col>
    </v-row>
    <v-row fluid>
      <v-col class="col" fluid>
    <v-card>
      <v-card-title>Skills</v-card-title>
      <v-card-subtitle>Languages and Frameworks</v-card-subtitle>
      <v-list rounded>

        <v-list-item href="https://Javascript.com" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/js.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Javascript</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://Vuejs.org" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/logo.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Vue.js ( Vuetify + Vuex )</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://Nodejs.org" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/node.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Node.js</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://docs.microsoft.com/en-us/dotnet/csharp/" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/csharp.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>C#/.NET</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://GraphQL.org" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/GraphQL.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>GraphQL</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://www.w3schools.com/sql/sql_intro.asp" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/SQL.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>SQL</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/HTML.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>HTML</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/CSS.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>CSS</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

      </v-list>
    </v-card>
    </v-col>
    <v-col class="col" fluid>
    <v-card >
      <v-card-title>Tools</v-card-title>
      <v-card-subtitle>Software</v-card-subtitle>
      <v-list rounded>

        <v-list-item href="https://code.visualstudio.com/" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/VSCode.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Visual Studio Code</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://visualstudio.microsoft.com/" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/VisualStudio.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Visual Studio</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://Prisma.io" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/PrismaGreen.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Prisma</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https:///apollographql.com/" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/Apollo.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Apollo</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://Postgresql.org" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/Postgres.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Postgres</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://docs.microsoft.com/en-us/sql/ssms/sql-server-management-studio-ssms?view=sql-server-ver15" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/MSSMS.svg"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>SSMS</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://getpostman.com/" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/Postman.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Postman</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item href="https://Swagger.io" target="blank">
          <v-list-item-avatar tile>
            <v-img src="@/assets/Swagger.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Swagger</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

      </v-list>
    </v-card>
    </v-col>
    <v-col class="col" fluic>
    <v-card>
      <v-card-title>Proficiencies</v-card-title>
      <v-card-subtitle>Industry Knowledge</v-card-subtitle>
      <v-list disabled rounded>

        <v-list-item >
          
          <v-list-item-avatar tile>
            <v-img src="@/assets/WebDev.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Web Development</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item>
          <v-list-item-avatar tile>
            <v-img src="@/assets/OOP.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Object Oriented Programming</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item>
          <v-list-item-avatar tile>
            <v-img src="@/assets/Mobile.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Mobile First Development</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item>
          <v-list-item-avatar tile>
            <v-img src="@/assets/Agile.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Agile Methodologies</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item>
          <v-list-item-avatar tile>
            <v-img src="@/assets/TDD.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Test Driven Development</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

        <v-list-item>
          <v-list-item-avatar tile>
            <v-img src="@/assets/DB.png"></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
            <v-list-item-title>Database Design</v-list-item-title>
          </v-list-item-content>
        </v-list-item>

      </v-list>
    </v-card>
    </v-col>
    </v-row>
  </div>
</template>



<style scoped>
.icon {
  max-height: 50px;
}
.card {
  margin-bottom: 2%;
}
.col {
background-color: rgb(20,20,20)
}
.page {
  background-color: rgb(20,20,20)
}
</style>
