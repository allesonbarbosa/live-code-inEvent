<template>
    <div id="container-feature-list">
        <h1>Features List</h1>
        <h2>If you prefer, you can choose cases by category</h2>
        <div id="container-buttons">
            <button id="btn-all" @click="filterList('all')">All</button>
            <button id="btn-start" @click="filterList('start')">Start</button>
            <button id="btn-registration" @click="filterList('registration')">Registration</button>
            <button id="btn-live" @click="filterList('live')">Live</button>
            <button id="btn-compliance" @click="filterList('compliance')">Compliance</button>
        </div>
        <div id="container-list">
            <div class="content-lists" v-for="feature in filteredFeatures" :key="feature.id">
                <p class="feature-name">{{feature.name}}</p>
                <p class="category-name">{{feature.category}}</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'FeatureList',
    data(){
        return{
            allFeatures:[
                { id: 0, name: 'Virtual Lobby', category: 'start'},
                { id: 1, name: 'Live App', category: 'start'},
                { id: 2, name: 'Multi-events', category: 'start'},
                { id: 3, name: 'Event website', category: 'registration'},
                { id: 4, name: 'Forms', category: 'registration'},
                { id: 5, name: 'Lists', category: 'registration'},
                { id: 6, name: 'Live Studio', category: 'live'},
                { id: 7, name: 'Video Conferencing', category: 'live'},
                { id: 8, name: 'Badge design', category: 'live'},
                { id: 9, name: 'Reports', category: 'compliance'},
                { id: 10, name: 'Virtual Lobby', category: 'compliance'},
            ],
            filteredFeatures:[
                { id: 0, name: 'Virtual Lobby', category: 'start'},
                { id: 1, name: 'Live App', category: 'start'},
                { id: 2, name: 'Multi-events', category: 'start'},
                { id: 3, name: 'Event website', category: 'registration'},
                { id: 4, name: 'Forms', category: 'registration'},
                { id: 5, name: 'Lists', category: 'registration'},
                { id: 6, name: 'Live Studio', category: 'live'},
                { id: 7, name: 'Video Conferencing', category: 'live'},
                { id: 8, name: 'Badge design', category: 'live'},
                { id: 9, name: 'Reports', category: 'compliance'},
                { id: 10, name: 'Virtual Lobby', category: 'compliance'},
            ]
        }
    },
    methods:{
        filterList(category){
            if(category === 'all'){
                this.filteredFeatures = this.allFeatures;
            }else{
                const filter = this.allFeatures.filter(feature => feature.category.includes(category));
                this.filteredFeatures = filter;
            }
        }
    }
}
</script>

<style scoped>
    #container-feature-list{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 15px;
    }
    h1{
        color: #333333;
        font-size: 50px;
    }
    h2{
        color: #333333;
        font-size: 18px;
    }
    #container-buttons{
        display: flex;
        flex-direction: row;
        gap: 20px;
    }
    #container-buttons button{
        color: #2C3242;
        background-color: #EEEEEF;
        padding: 8px;
        font-size: 18px;
        font-weight: bold;
        text-transform: uppercase;
        border: none;
    }
    #container-buttons button:hover{
        color: #0078CB;
        background-color: #D2ECFF;
        cursor: pointer;
        transition: 0.5s;
    }
    .content-lists{
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center;
        gap: 50px
    }
    .feature-name{
        width: 200px;
        text-align: center;
        font-size: 22px;
        margin-bottom: 15px;
    }
    .category-name{
        width: 150px;
        text-align: center;
        font-size: 22px;
        margin-bottom: 15px;
    }
</style>