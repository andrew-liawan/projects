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

The following table shows the Top 100 Songs of the 2nd week of November 2024

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
| 21  | -1   | Hot To Go                       | Chappell Roan                                           | 10   | 25 |
| 22  | NEW  | Sao Paolo                       | The Weeknd ft. Anitta                                   | 22   | 1  |
| 23  | +6   | Lose Control                    | Teddy Swims                                             | 4    | 52 |
| 24  | -1   | Diet Pepsi                      | Addison Rae                                             | 21   | 11 |
| 25  | +1   | Mantra                          | JENNIE                                                  | 19   | 4  |
| 26  | +6   | Love Somebody                   | Morgan Wallen                                           | 26   | 3  |
| 27  | +6   | Embrace It                      | Ndotz                                                   | 27   | 8  |
| 28  | +2   | Not Like Us                     | Kendrick Lamar                                          | 2    | 27 |
| 29  | -1   | The Door                        | Teddy Swims                                             | 20   | 23 |
| 30  | -3   | Rah Tah Tah                     | Tyler, The Creator                                      | 27   | 2  |
| 31  | -18  | Noid                            | Tyler, The Creator                                      | 13   | 3  |
| 32  | -7   | Miles On It                     | Marshmello & Kane Brown                                 | 18   | 27 |
| 33  | -15  | Disease                         | Lady Gaga                                               | 18   | 2  |
| 34  | +3   | Stargazing                      | Myles Smith                                             | 8    | 26 |
| 35  | +9   | Sticky                          | Tyler, The Creator ft. GloRilla, Sexxy Red & Lil Wayne  | 35   | 2  |
| 36  | 0    | Million Dollar Baby             | Tommy Richman                                           | 4    | 28 |
| 37  | +3   | Thick Of It                     | KSI ft. Trippie Redd                                    | 37   | 5  |
| 38  | -4   | Guess                           | Charli XCX ft. Billie Eilish                            | 5    | 14 |
| 39  | +2   | Austin (Boots Stop Workin')     | Dasha                                                   | 10   | 38 |
| 40  | -2   | Cowgirls                        | Morgan Wallen ft. ERNEST                                | 31   | 19 |
| 41  | +7   | Close To You                    | Gracie Abrams                                           | 29   | 22 |
| 42  | -3   | Si Antes Te Hubiera Conocido    | KAROL G                                                 | 22   | 15 |
| 43  | +4   | Touch                           | KATSEYE                                                 | 43   | 9  |
| 44  | -13  | Darling, I                      | Tyler, The Creator ft. Teezo Touchdown                  | 31   | 2  |
| 45  | -2   | Pink Pony Club                  | Chappell Roan                                           | 17   | 21 |
| 46  | -4   | The Emptiness Machine           | Linkin Park                                             | 8    | 9  |
| 47  | +3   | I Can Do It With A Broken Heart | Taylor Swift                                            | 5    | 29 |
| 48  | -2   | Move                            | Adam Port & Stryv ft. Malachiii                         | 25   | 18 |
| 49  | +2   | Mamushi                         | Megan Thee Stallion ft. Yuki Chiba                      | 25   | 19 |
| 50  | -1   | Pink Skies                      | Zach Bryan                                              | 24   | 24 |
| 51  | +1   | New Drop                        | Don Toliver                                             | 51   | 7  |
| 52  | -7   | Ain't No Love In Oklahoma       | Luke Combs                                              | 39   | 18 |
| 53  | +6   | Why Why Why                     | Shawn Mendes                                            | 36   | 13 |
| 54  | +6   | It's Ok I'm Ok                  | Tate McRae                                              | 10   | 8  |
| 55  | +7   | Dancing In The Flames           | The Weeknd                                              | 7    | 8  |
| 56  | +25  | Bad Dreams                      | Teddy Swims                                             | 44   | 8  |
| 57  | -1   | Carry You Home                  | Alex Warren                                             | 49   | 13 |
| 58  | -1   | Burning Down                    | Alex Warren                                             | 55   | 7  |
| 59  | +5   | Soltera                         | Shakira                                                 | 58   | 6  |
| 60  | +10  | Juno                            | Sabrina Carpenter                                       | 25   | 11 |
| 61  | -6   | 28                              | Zach Bryan                                              | 38   | 18 |
| 62  | +10  | We Pray                         | Coldplay                                                | 61   | 11 |
| 63  | -9   | Alibi                           | Sevdaliza, Pabllo Vittar & Yseult                       | 20   | 17 |
| 64  | -29  | I'll Be There                   | Jin                                                     | 35   | 2  |
| 65  | +10  | Lonely Road                     | mgk & Jelly Roll                                        | 46   | 13 |
| 66  | +3   | Uwaie                           | Kapo                                                    | 56   | 10 |
| 67  | +6   | Heavy Is The Crown              | Linkin Park                                             | 15   | 7  |
| 68  | +26  | Like Him                        | Tyler, The Creator ft. Lola Young                       | 68   | 2  |
| 69  | +10  | Degenere                        | Myke Towers ft. benny blanco                            | 69   | 3  |
| 70  | -12  | Thought I Was Dead              | Tyler, The Creator ft. ScHoolboy Q & Santigold          | 58   | 2  |
| 71  | -4   | Gata Only                       | FloyyMenor & Cris Mj                                    | 39   | 18 |
| 72  | +4   | Sympathy Is A Knife             | Charli XCX ft. Ariana Grande                            | 27   | 4  |
| 73  | -2   | Whiplash                        | aespa                                                   | 71   | 3  |
| 74  | +11  | Girls                           | The Kid LAROI                                           | 43   | 19 |
| 75  | +12  | Stumblin' In                    | CYRIL                                                   | 74   | 11 |
| 76  | -8   | Apple                           | Charli XCX                                              | 20   | 18 |
| 77  | +3   | Tu Boda                         | Oscar Maydon & Fuerza Regida                            | 77   | 3  |
| 78  | +14  | A Lot More Free                 | Max McNown                                              | 70   | 5  |
| 79  | +7   | Feelslikeiamfallinginlove       | Coldplay                                                | 56   | 20 |
| 80  | -3   | Disco                           | Surf Curse                                              | 48   | 10 |
| 81  | -7   | Big Dawgs                       | Hanumankind & Kalmi                                     | 13   | 15 |
| 82  | +2   | Baby I'm Back                   | The Kid LAROI                                           | 59   | 11 |
| 83  | NEW  | Chill Bae                       | Lil Uzi Vert                                            | 83   | 1  |
| 84  | -19  | Judge Judy                      | Tyler, The Creator                                      | 65   | 2  |
| 85  | +3   | Kisses                          | BL3SS & CarminWatsin ft. bbyclose                       | 78   | 6  |
| 86  | -33  | Hey Jane                        | Tyler, The Creator                                      | 53   | 2  |
| 87  | -5   | Keep Up                         | Odetari                                                 | 62   | 8  |
| 88  | RE   | Casual                          | Chappell Roan                                           | 61   | 19 |
| 89  | +4   | You Look Like You Love Me       | Ella Langley ft. Riley Green                            | 68   | 13 |
| 90  | RE   | Good Graces                     | Sabrina Carpenter                                       | 17   | 10 |
| 91  | -1   | Backbone                        | Chase & Status & Stormzy                                | 61   | 13 |
| 92  | -26  | Take Your Mask Off              | Tyler, The Creator ft. Daniel Caesar & LaToiya Williams | 66   | 2  |
| 93  | NEW  | Heart Of Gold                   | Shawn Mendes                                            | 93   | 1  |
| 94  | -3   | Pour Me A Drink                 | Post Malone ft. Blake Shelton                           | 23   | 20 |
| 95  | +5   | Guy For That                    | Post Malone ft. Luke Combs                              | 22   | 15 |
| 96  | NEW  | Light Year (Practice)           | Lil Uzi Vert                                            | 96   | 1  |
| 97  | RE   | Pretty Slowly                   | Benson Boone                                            | 76   | 6  |
| 98  | RE   | I Like It                       | Alesso & Nate Smith                                     | 71   | 14 |
| 99  | 0    | New Woman                       | LISA ft. ROSALIA                                        | 17   | 12 |
| 100 | -5   | Fuel                            | Eminem & JID                                            | 27   | 10 |

#### Year Points.xlsx

The following table shows the Top 100 Songs of 2024 based on Year-End calculations

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
| 21    | End Of Beginning                         | Djo                                                      | 4    | 27 | 3237 |
| 22    | Houdini                                  | Dua Lipa                                                 | 2    | 27 | 3207 |
| 23    | Water                                    | Tyla                                                     | 9    | 33 | 3205 |
| 24    | Stargazing                               | Myles Smith                                              | 8    | 26 | 3104 |
| 25    | Paint The Town Red                       | Doja Cat                                                 | 1    | 36 | 3066 |
| 26    | I Can Do It With A Broken Heart          | Taylor Swift                                             | 5    | 29 | 3027 |
| 27    | Strangers                                | Kenya Grace                                              | 6    | 31 | 2938 |
| 28    | Fortnight                                | Taylor Swift ft. Post Malone                             | 1    | 22 | 2926 |
| 29    | Texas Hold 'Em                           | Beyonce                                                  | 2    | 21 | 2900 |
| 30    | Die With A Smile                         | Lady Gaga & Bruno Mars                                   | 1    | 12 | 2820 |
| 31    | Saturn                                   | SZA                                                      | 7    | 23 | 2716 |
| 32    | Hot To Go                                | Chappell Roan                                            | 10   | 25 | 2682 |
| 33    | I Like The Way You Kiss Me               | Artemas                                                  | 3    | 20 | 2641 |
| 34    | Vampire                                  | Olivia Rodrigo                                           | 1    | 42 | 2627 |
| 35    | Redrum                                   | 21 Savage                                                | 7    | 21 | 2549 |
| 36    | Yes, And?                                | Ariana Grande                                            | 1    | 20 | 2505 |
| 37    | Lunch                                    | Billie Eilish                                            | 1    | 21 | 2500 |
| 38    | Like That                                | Future, Metro Boomin & Kendrick Lamar                    | 3    | 21 | 2436 |
| 39    | Popular                                  | The Weeknd, Playboi Carti & Madonna                      | 9    | 46 | 2333 |
| 40    | Who                                      | Jimin                                                    | 5    | 16 | 2332 |
| 41    | Standing Next To You                     | Jung Kook                                                | 8    | 20 | 2308 |
| 42    | I Remember Everything                    | Zach Bryan ft. Kacey Musgraves                           | 11   | 34 | 2293 |
| 43    | Agora Hills                              | Doja Cat                                                 | 8    | 26 | 2262 |
| 44    | Belong Together                          | Mark Ambor                                               | 18   | 23 | 2155 |
| 45    | What Was I Made For?                     | Billie Eilish                                            | 3    | 37 | 2084 |
| 46    | Snooze                                   | SZA                                                      | 6    | 50 | 2073 |
| 47    | Thinkin' Bout Me                         | Morgan Wallen                                            | 16   | 27 | 2071 |
| 48    | Is It Over Now? (Taylor's Version)       | Taylor Swift                                             | 1    | 20 | 2057 |
| 49    | Miles On It                              | Marshmello & Kane Brown                                  | 18   | 27 | 2038 |
| 50    | Carnival                                 | Y$, K. West, Ty Dolla $ign, Rich The Kid & Playboi Carti | 4    | 20 | 1995 |
| 51    | Houdini                                  | Eminem                                                   | 3    | 20 | 1986 |
| 52    | Taste                                    | Sabrina Carpenter                                        | 2    | 11 | 1940 |
| 53    | Wildflower                               | Billie Eilish                                            | 11   | 25 | 1895 |
| 54    | Magnetic                                 | ILLIT                                                    | 14   | 20 | 1883 |
| 55    | I Don't Wanna Wait                       | David Guetta & OneRepublic                               | 18   | 23 | 1876 |
| 56    | Exes                                     | Tate McRae                                               | 12   | 20 | 1852 |
| 57    | Prada                                    | casso, RAYE & D-Block Europe                             | 13   | 29 | 1846 |
| 58    | Unwritten                                | Natasha Bedingfield                                      | 13   | 20 | 1819 |
| 59    | Chihiro                                  | Billie Eilish                                            | 6    | 20 | 1798 |
| 60    | Training Season                          | Dua Lipa                                                 | 11   | 21 | 1795 |
| 61    | Surround Sound                           | JID ft. 21 Savage & Baby Tate                            | 13   | 20 | 1781 |
| 62    | 3D                                       | Jung Kook ft. Jack Harlow                                | 3    | 21 | 1768 |
| 63    | Slow It Down                             | Benson Boone                                             | 22   | 21 | 1768 |
| 64    | Pink Skies                               | Zach Bryan                                               | 24   | 24 | 1766 |
| 65    | The Boy Is Mine                          | Ariana Grande                                            | 9    | 24 | 1750 |
| 66    | Feather                                  | Sabrina Carpenter                                        | 17   | 22 | 1749 |
| 67    | Dance The Night                          | Dua Lipa                                                 | 3    | 41 | 1747 |
| 68    | Guess                                    | Charli XCX ft. Billie Eilish                             | 5    | 14 | 1688 |
| 69    | Pink Pony Club                           | Chappell Roan                                            | 17   | 21 | 1684 |
| 70    | Fein                                     | Travis Scott ft. Playboy Carti                           | 8    | 35 | 1672 |
| 71    | 360                                      | Charli XCX                                               | 17   | 21 | 1643 |
| 72    | Monaco                                   | Bad Bunny                                                | 13   | 20 | 1594 |
| 73    | Scared To Start                          | Michael Marcagi                                          | 18   | 20 | 1574 |
| 74    | Made For Me                              | Muni Long                                                | 25   | 24 | 1571 |
| 75    | Band4band                                | Central Cee ft. Lil Baby                                 | 15   | 19 | 1571 |
| 76    | The Night We Met                         | Lord Huron                                               | 22   | 23 | 1532 |
| 77    | Type Shit                                | Future, Metro Boomin, Travis Scott & Playboy Carti       | 15   | 20 | 1523 |
| 78    | IDGAF                                    | Drake ft. Yeat                                           | 4    | 20 | 1518 |
| 79    | Flowers                                  | Miley Cyrus                                              | 1    | 60 | 1504 |
| 80    | Bed Chem                                 | Sabrina Carpenter                                        | 9    | 11 | 1469 |
| 81    | The Door                                 | Teddy Swims                                              | 20   | 23 | 1469 |
| 82    | Can't Catch Me Now                       | Olivia Rodrigo                                           | 15   | 20 | 1463 |
| 83    | Lil Boo Thang                            | Paul Russell                                             | 23   | 20 | 1436 |
| 84    | Murder On The Dancefloor                 | Sophie Ellis-Bextor                                      | 10   | 19 | 1405 |
| 85    | Red Wine Supernova                       | Chappell Roan                                            | 28   | 20 | 1398 |
| 86    | Praise Jah In The Moonlight              | YG Marley                                                | 13   | 16 | 1394 |
| 87    | Big Dawgs                                | Hanumankind & Kalmi                                      | 13   | 15 | 1387 |
| 88    | Whatever                                 | Kygo & Ava Max                                           | 36   | 22 | 1359 |
| 89    | Mamushi                                  | Megan Thee Stallion ft. Yuki Chiba                       | 25   | 19 | 1347 |
| 90    | Evergreen                                | Richy Mitch & The Coal Miners                            | 27   | 22 | 1319 |
| 91    | Move                                     | Adam Port & Stryv ft. Malachiii                          | 25   | 18 | 1312 |
| 92    | Nasty                                    | Tinashe                                                  | 29   | 20 | 1303 |
| 93    | Apple                                    | Charli XCX                                               | 20   | 18 | 1284 |
| 94    | Alibi                                    | Sevdaliza, Pabllo Vittar & Yseult                        | 20   | 17 | 1281 |
| 95    | Cowgirls                                 | Morgan Wallen ft. ERNEST                                 | 31   | 19 | 1275 |
| 96    | Intro (End Of The World)                 | Ariana Grande                                            | 32   | 20 | 1274 |
| 97    | Sailor Song                              | Gigi Perez                                               | 6    | 15 | 1246 |
| 98    | Kehlani                                  | Jordan Adetunji                                          | 25   | 20 | 1227 |
| 99    | Fukumean                                 | Gunna                                                    | 7    | 34 | 1225 |
| 100   | Nights Like This                         | The Kid LAROI                                            | 35   | 20 | 1215 |

### Download Excel Sheets

[Top 100 Chart](Top%20100%20Chart/Top%20100%20Chart.xlsx)

[Year Points](Markov%20Chain/Year%20Points.xlsx)


