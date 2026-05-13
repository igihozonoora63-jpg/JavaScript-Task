<template>
    <body>
        <header>
            <div class="buttons">
            <button @click="day = 'Monday'">Monday</button>
            <button @click="day = 'Tuesday'">Tuesday</button>
            <button @click="day = 'Wednesday'">Wednesday</button>
            <button @click="day = 'Thursday'">Thursday</button>
            <button @click="day = 'Friday'">Friday</button>
            </div>
        </header>
        <main>
            <div v-if="day === 'Monday'">Monday
            <table border="1">
                <tr>
                    <th colspan="13">Monday</th>>
                </tr>
                <tr>
                    <th>1</th>
                    <th>2</th>
                    <th>3</th>
                    <th>BREAK</th>
                    <th>4</th>
                    <th>5</th>
                    <th>6</th>
                    <th>LUNCH</th>
                    <th>7</th>
                    <th>8</th>
                    <th>BREAK</th>
                    <th>9</th>
                    <th>10</th>
                </tr>
                <tr>
                    <td>Maths</td>
                    <td>Maths</td>
                    <td>Maths</td>
                    <td class="break">BREAK</td>
                    <td>English</td>
                    <td>English</td>
                    <td></td>
                    <td class="lunch">LUNCH</td>
                    <td>Science</td>
                    <td>Science</td>
                    <td class="break">BREAK</td>
                    <td>History</td>
                    <td>History</td>
                </tr>
                
            </table>
            <div class="activities">
                <ul>
                    <li>Do Mathematics exercises from pg 12 to 15</li>
                    <li>Read Chapter 3 of the English textbook</li>
                    <li>Complete the Science lab report</li>
                    <li>Review History notes for the upcoming test</li>
                </ul>
            </div>
            </div>
            <div v-if="day === 'Tuesday'">Tuesday
            <table border="1">
                <tr>
                    <th colspan="13">Tuesday</th>
                </tr>
                <tr>
                    <th>1</th>
                    <th>2</th>
                    <th>3</th>
                    <th>BREAK</th>
                    <th>4</th>
                    <th>5</th>
                    <th>6</th>
                    <th>LUNCH</th>
                    <th>7</th>
                    <th>8</th>
                    <th>BREAK</th>
                    <th>9</th>
                    <th>10</th>
                </tr>
                <tr>
                    <td>English</td>
                    <td>English</td>
                    <td>Physics</td>
                    <td class="break">BREAK</td>
                    <td>Maths</td>
                    <td>Maths</td>
                    <td></td>
                    <td class="lunch">LUNCH</td>
                    <td>Chemistry</td>
                    <td>History</td>
                    <td class="break">BREAK</td>
                    <td>Science</td>
                    <td>Science</td>
                </tr>

            </table>
            <div class="activities">
                <ul>
                    <li>Complete Physics project on chapter 13</li>
                    <li>Practice English grammar exercises</li>
                    <li>Study for the upcoming Maths quiz</li>
                </ul>

            </div>

            </div>
            <div v-if="day === 'Wednesday'">Wednesday
                <table border="1">
                    <tr>
                        <th colspan="13">Wednesday</th>
                    </tr>
                    <tr>
                        <th>1</th>
                        <th>2</th>
                        <th>3</th>
                        <th>BREAK</th>
                        <th>4</th>
                        <th>5</th>
                        <th>6</th>
                        <th>LUNCH</th>
                        <th>7</th>
                        <th>8</th>
                        <th>BREAK</th>
                        <th>9</th>
                        <th>10</th>
                    </tr>
                    <tr>
                        <td>Chemistry</td>
                        <td>Chemistry</td>
                        <td>Maths</td>
                        <td class="break">BREAK</td>
                        <td>English</td>
                        <td></td>
                        <td></td>
                        <td class="lunch">LUNCH</td>
                        <td>History</td>
                        <td></td>
                        <td class="break">BREAK</td>
                        <td>Science</td>
                        <td></td>

                    </tr>
                    </table>
            </div>
           
            <div v-if="day === 'Thursday'">Thursday
                <table border="1">
                    <tr>
                        <th colspan="13">Thursday</th>
                    </tr>
                    <tr>
                        <th>1</th>
                        <th>2</th>
                        <th>3</th>
                        <th>BREAK</th>
                        <th>4</th>
                        <th>5</th>
                        <th>6</th>
                        <th>LUNCH</th>
                        <th>7</th>
                        <th>8</th>
                        <th>BREAK</th>
                        <th>9</th>
                        <th>10</th>
                    </tr>
                    <tr>
                        <td>History</td>
                        <td></td>
                        <td></td>
                        <td class="break">BREAK</td>
                        <td>Chemistry</td>
                        <td>Chemistry</td>
                        <td></td>
                        <td class="lunch">LUNCH</td>
                        <td>Maths</td>
                        <td>Maths</td>
                        <td class="break">BREAK</td>
                        <td>English</td>
                        <td></td>

                    </tr>
                </table>
               
            </div>
            <div v-if="day === 'Friday'">Friday
                <table border="1">
                           <tr>
                        <th colspan="13">Friday</th>
                    </tr>
                    <tr>
                        <th>1</th>
                        <th>2</th>
                        <th>3</th>
                        <th>BREAK</th>
                        <th>4</th>
                        <th>5</th>
                        <th>6</th>
                        <th>LUNCH</th>
                        <th>7</th>
                        <th>8</th>
                        <th>BREAK</th>
                        <th>9</th>
                        <th>10</th>
                    </tr>
                    <tr>
                        <td>History</td>
                        <td></td>
                        <td></td>
                        <td class="break">BREAK</td>
                        <td>Chemistry</td>
                        <td>Chemistry</td>
                        <td></td>
                        <td class="lunch">LUNCH</td>
                        <td>Maths</td>
                        <td>Maths</td>
                        <td class="break">BREAK</td>
                        <td>English</td>
                        <td></td>

                    </tr>
                </table>
                <div class= "activities">
                    <ul>
                        <li>Review History notes and complete practice problems</li>
                        <li>Work on English essay assignment</li>
                        <li>Prepare for the History presentation</li>
                    </ul>
                </div>
            </div>
                
            
        </main>
    </body>

</template>
<script>
export default {
    data() {
        return {
            day: "Monday"
        }
    }
}
</script>
<style>
.buttons {
    display: flex;
    justify-content: center;
    margin-top: 20px;
}
.buttons button {
    margin: 0 10px;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}
.activities {
    margin-top: 20px;
    padding: 10px;
    background-color: #f0f0f0;
    border-radius: 5px;
}
.activities ul {
    list-style-type: disc;
    padding-left: 20px;
}
.activities li {
    margin-bottom: 10px; 
}
</style>