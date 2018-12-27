<div id="app">
<h1>To Do List (With Vue.js)</h1>
<ul class="list" v-if="items.length">
    {{item}}
    <span class="remove-item-button" @click="remove(index)">
        +
    </span>
    </li>
</ul>

<div v-if="!items.length" class="empty-list-msg">
empty
</div>
    <input type="text"
    placeholder="New task..."
    v-model="currentValue"
    />
<button @click= "add" : disabled="!cureentValue">
    Add task
</button>

</div>