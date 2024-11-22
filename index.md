# PROJECTS

These are data-related formal studies projects and passion/hobby-related projects. 

## 90s Artists

### Description

### Dashboard

<div id="viz1732225136556" class="tableauPlaceholder"
style="position: relative">

<noscript>
<a href='#'><img alt='Recognizability of 90&#39;s Artists in 2020 by Millenials and Gen-Zs - Andrew Liawan ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;Recognitionof90sartists&#47;Recognizabilityof90sArtistsin2020byMillenialsandGen-Zs-AndrewLiawan&#47;1_rss.png' style='border: none' /></a>
</noscript>
<object class="tableauViz" style="display:none;">
<param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
<param name='embed_code_version' value='3' />
<param name='site_root' value='' /><param name='name' value='Recognitionof90sartists&#47;Recognizabilityof90sArtistsin2020byMillenialsandGen-Zs-AndrewLiawan' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Re&#47;Recognitionof90sartists&#47;Recognizabilityof90sArtistsin2020byMillenialsandGen-Zs-AndrewLiawan&#47;1.png' />
<param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' />
</object>

</div>

<script>
                    var divElement = document.getElementById('viz1732225136556');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1527px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>



## Markov Chains

### Description

This folder contains R-Code and PDF of one of my statistics projects in school. It is a theoretical dive on hypothesis testing test statistic and methodologies on multiple Markov chains. They contain data simulations and analysis on why a certain way of hypothesis testing works in this particular case of Markov chains.

R-Code is in the form of a HTML, and PDF is in a form of a short scientific journal.

### Links to Reports

[Journal Report PDF](Markov%20Chain/STAT%20403%20Project%20-%20Andrew%20Liawan.pdf)

[R Code (HTML)](Markov%20Chain/STAT-403-Project.html)

## Top 100 Charts

### Description

This project is a snapshot of the use of Excel skills in one of my hobbies, being music and mainstream songs in general. These track the popularity of songs in a weekly basis throughout the year, as well as using the weekly results to calculate year-end popularity of every song in 2024.

This project contains the 2 following excel spreadsheets.

#### Top 100 Chart.xlsx

This Microsoft Excel file contains the top 100 songs of every week in the year 2024. In a technical standpoint, this file demonstrates my skills in Excel in SPSS calculations such as VLOOKUP and IF functions and conditional rules on cell colors. The spreadsheet is also built in a way that its format can be adapted to external power querying into other excel spreadsheets or Power BI environments.

Visible Columns:
- No. : Weekly position of the song that particular week
    - NEW : First/Debut entry of a new song that particular week
    - RE : Song re-entered the Top 100 after completely exiting the charts
- LW : Movement of position of the song compared to last week (ex. +3 means the song jumped 3 positions from last week)
- Song : Title of the song
- Artist: Artist(s) of the song
- Peak : The peak position of the song
- WO : The number of weeks that the song charted

#### Year Points.xlsx

This Microsoft Excel file takes data from the Top 100 Chart.xlsx spreadsheet, assign points to each song every week based on how well they perform in the weekly charts, and add the points up throughout the year, creating a table of the overall popularity of the songs in 2024 based on the assigned points. This file demonstrates my ability to extract data from another spreadsheet and incorporating a reference table to create a new database from another database, all using Excel’s built-in Power Query

### Sample Tables

#### Top 100 Chart.xlsx

The following table shows the Top 100 Songs of the 2nd week of November 2024 (top 20 rows shown)

| No. | LW   | Song                            | Artist                                                  | Peak | WO |
| --- | ---- | ------------------------------- | ------------------------------------------------------- | ---- | -- |
| 1   | +1   | Die With A Smile                | Lady Gaga & Bruno Mars                                  | 1    | 12 |
| 2   | -1   | APT.                            | ROSE ft. Bruno Mars                                     | 1    | 3  |
| 3   | 0    | Birds Of A Feather              | Billie Eilish                                           | 1    | 25 |
| 4   | 0    | Taste                           | Sabrina Carpenter                                       | 2    | 11 |
| 5   | 0    | Espresso                        | Sabrina Carpenter                                       | 1    | 30 |
| 6   | +2   | Sailor Song                     | Gigi Perez                                              | 6    | 15 |
| 7   | -1   | A Bar Song (Tipsy)              | Shaboozey                                               | 1    | 30 |
| 8   | -1   | Good Luck, Babe!                | Chappell Roan                                           | 4    | 31 |
| 9   | +1   | Who                             | Jimin                                                   | 5    | 16 |
| 10  | +5   | That's So True                  | Gracie Abrams                                           | 10   | 3  |
| 11  | 0    | Wildflower                      | Billie Eilish                                           | 11   | 25 |
| 12  | -3   | Timeless                        | The Weeknd & Playboi Carti                              | 3    | 6  |
| 13  | -1   | Please Please Please            | Sabrina Carpenter                                       | 1    | 22 |
| 14  | +3   | I Love You, I'm Sorry           | Gracie Abrams                                           | 14   | 15 |
| 15  | +1   | St. Chroma                      | Tyler, The Creator ft. Daniel Caesar                    | 15   | 2  |
| 16  | +3   | Beautiful Things                | Benson Boone                                            | 1    | 42 |
| 17  | +4   | Too Sweet                       | Hozier                                                  | 1    | 33 |
| 18  | -4   | Bed Chem                        | Sabrina Carpenter                                       | 9    | 11 |
| 19  | +3   | Moonlit Floor                   | LISA                                                    | 19   | 5  |
| 20  | +4   | I Had Some Help                 | Post Malone ft. Morgan Wallen                           | 1    | 26 |


#### Year Points.xlsx

The following table shows the Top 100 Songs of 2024 based on Year-End calculations (top 20 rows shown)

| Index | Song                                     | Artist                                                   | Peak | WO | Pts  |
| ----- | ---------------------------------------- | -------------------------------------------------------- | ---- | -- | ---- |
| 1     | Beautiful Things                         | Benson Boone                                             | 1    | 42 | 6775 |
| 2     | Greedy                                   | Tate McRae                                               | 1    | 41 | 5896 |
| 3     | Espresso                                 | Sabrina Carpenter                                        | 1    | 30 | 5878 |
| 4     | Lose Control                             | Teddy Swims                                              | 4    | 52 | 5877 |
| 5     | Cruel Summer                             | Taylor Swift                                             | 1    | 67 | 5145 |
| 6     | Too Sweet                                | Hozier                                                   | 1    | 33 | 5020 |
| 7     | A Bar Song (Tipsy)                       | Shaboozey                                                | 1    | 30 | 4800 |
| 8     | Stick Season                             | Noah Kahan                                               | 3    | 43 | 4705 |
| 9     | Birds Of A Feather                       | Billie Eilish                                            | 1    | 25 | 4608 |
| 10    | One Of The Girls                         | The Weeknd, JENNIE & Lily-Rose Depp                      | 1    | 38 | 4359 |
| 11    | My Love Mine All Mine                    | Mitski                                                   | 3    | 38 | 4170 |
| 12    | Good Luck, Babe!                         | Chappell Roan                                            | 4    | 31 | 4149 |
| 13    | I Had Some Help                          | Post Malone ft. Morgan Wallen                            | 1    | 26 | 4133 |
| 14    | Austin (Boots Stop Workin')              | Dasha                                                    | 10   | 38 | 4102 |
| 15    | Lovin On Me                              | Jack Harlow                                              | 2    | 30 | 4100 |
| 16    | Not Like Us                              | Kendrick Lamar                                           | 2    | 27 | 3853 |
| 17    | Please Please Please                     | Sabrina Carpenter                                        | 1    | 22 | 3695 |
| 18    | Million Dollar Baby                      | Tommy Richman                                            | 4    | 28 | 3597 |
| 19    | We Can't Be Friends (Wait For Your Love) | Ariana Grande                                            | 1    | 30 | 3508 |
| 20    | Seven                                    | Jung Kook ft. Latto                                      | 1    | 40 | 3324 |


### Download Excel Sheets

[Top 100 Chart](Top%20100%20Chart/Top%20100%20Chart.xlsx)

[Year Points](Top%20100%20Chart/Year%20Points.xlsx)


