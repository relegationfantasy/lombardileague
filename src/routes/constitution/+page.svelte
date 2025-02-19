<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">RELEGATION FANTASY RULES & GUIDELINES</h1>    
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1 Registration & Assignment</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>1.1 New Players</h3>

    <p>After registration on www.relegationfantasy.com, new players will receive an invoice at the email they signed up with. This invoice will include league fees and the buy-in for their assigned league. LEAGUE FEES FOR ALL PLAYERS ARE DUE BY JULY 31ST.</p>

    <p>After payment is made, players will then receive an email with the invite link to join their RFL league on Sleeper.</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>1.2 Returning Players</h3>

    <p>Returning players will receive an invoice after the conclusion of the previous fantasy season that will allow them to secure their spot in the following year's league. They will also be able to opt-out in this same email. LEAGUE FEES FOR ALL PLAYERS ARE DUE BY JULY 31st.</p>

    <p>Players who choose to sit out of a year or deny their invitation to play in the following year will have to restart their RFL journey at the lowest available tier if they choose to return later on.</p>

    <h2 class="sectionHeading" bind:this={one}>Section 2 Roster</h2>

    <p>28 Total Players</p>
    
    <h3 class="subSectionHeading" bind:this={TwoOne}>2.2 Starters</h3> 

    <ul>
        <li>QB</li>
        <li>RB</li>
        <li>RB</li>
        <li>WR</li>
        <li>WR</li>
        <li>WR</li>
        <li>TE</li>
        <li>FLEX (RB/WR/TE)</li>
        <li>SUPERFLEX</li>
    </ul>

    <h3 class="subSectionHeading" bind:this={TwoTwo}>2.2 Bench</h3> 

    <p>7 Bench spots</p>

    <p>2 IR spots (Includes players listed as Out in the Sleeper App)</p>
    
    <h3 class="subSectionHeading" bind:this={TwoThree}>2.3 Position Limits</h3> 
        
    <ul>
        <li>QB (4)</li>
        <li>RB (6)</li>
        <li>WR (7)</li>
        <li>TE (4)</li>
    </ul>

    <h3 class="subSectionHeading" bind:this={TwoFour}>2.4 Waivers</h3> 

    <p>Free Agent Acquisition Budget (FAAB)</p>

    <p>$150 ($1 minimum bid)​</p>

    <p>Waivers clear Wednesday at 3 AM EST (Players are on waivers for 2 days after they are dropped)</p>

    <h2 class="sectionHeading" bind:this={one}>Section 3 Scoring</h2>

    <h3 class="subSectionHeading" bind:this={oneTwo}>3.1 Points System</h3>

    <p>ESPN Standard PPR Scoring (EXCEPTION: Tight End Premium (TEs get 1.5 points per reception)</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>3.2 League Median</h3>

    <p>Each week, teams in the top 6 points scored for the week will receive an extra win, and teams in the bottom 6 points scored will receive and extra loss (This function does not operate during the playoffs)</p>

    <h2 class="sectionHeading" bind:this={one}>Section 4 Trading</h2>

    <h3 class="subSectionHeading" bind:this={oneTwo}>4.1 Vetoes</h3>

    <p>Managers within RFL leagues have no power to veto trades (The RFL Commissioner may veto a trade if it is deemed to be unethical)</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>4.2 Multi-Team Trades</h3>

    <p>Multi-team trades are legal in any capacity (Trades can be conducted between anywhere from 2-12 teams)</p>

    <h2 class="sectionHeading" bind:this={one}>Section 5 Draft</h2>

    <h3 class="subSectionHeading" bind:this={oneTwo}>5.1 Draft Date</h3>

    <p>Drafts for all leagues will take place on the same date. The league office will select this date. (date will be set at least a month before the draft)</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>5.2 Draft Style</h3>

    <p>Drafts will be in the SNAKE format.</p>

    <p>Drafts will be in a slow draft format with 12 hours per pick. If the player is selected then it will advance to the next pick. (If an owner misses a pick then autodraft will be turned on for their following picks unless they resume picking later on)</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>5.3 Third Round Reversal</h3>

    <p>The order of the draft will reverse at the end of the second round and then stay that way for the remainder of the draft.</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>5.4 Selection Order</h3>

    <p>Selection order will be randomized and input into the Sleeper app at least 3 weeks before the draft date.</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>5.5 Trading Draft Picks</h3>

    <p>The trading of draft picks is strictly prohibited</p>

    <h2 class="sectionHeading" bind:this={one}>Section 6 Schedule</h2>

    <h3 class="subSectionHeading" bind:this={oneTwo}>6.1 Divisions</h3>

    <p>Each league will contain one large division. Every team within the league will play each other at least once per season.</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>6.2 Trade Deadline</h3>

    <p>The trade deadline will be on week 12 of the NFL season.</p>

    <h2 class="sectionHeading" bind:this={one}>Section 7 Playoffs</h2>

    <h3 class="subSectionHeading" bind:this={oneTwo}>7.1 Start</h3>

    <p>The playoffs will start on week 14 of the NFL season. Each round will be one week of the NFL season.</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>7.2 Teams</h3>

    <p>The top 8 teams in the league will make the playoffs.</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>7.3 Seeding</h3>

    <p>Teams will be seeded by their overall record (Points for will be the tiebreak)</p>

    <h2 class="sectionHeading" bind:this={one}>Section 8 Promotion & Relegation</h2>

    <h3 class="subSectionHeading" bind:this={oneTwo}>8.1 Promotion</h3>

    <p>The champion of each CHALLENGER league will be promoted to the league tier directly above theirs.</p>

    <p>The top 4 teams within the BRONZE, SILVER, & GOLD league will be promoted to the league directly above theirs.</p>

    <p>Promotion can be denied by the manager (If promotion is denied, the promotion status will be passed to the next eligible player within that league)</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>8.2 Relegation</h3>

    <p>The bottom 4 teams (teams who miss the playoffs) in each league will be relegated to the league directly below theirs.​</p>

    <p>Teams who are relegated from the BRONZE league and all tiers below will be split into the 4 leagues directly below them.</p>

    <p>Relegation cannot be denied.</p>

     <h2 class="sectionHeading" bind:this={one}>Section 9 Player Ethics</h2>

    <p>All players are required to compete to win every game of every season in which they participate. If any player is found to be teaming with other players, participating in unethical trades to stack teams, intentionally losing games to aid other teams, promises for future league competition, or any other form of cheating, they will be removed from the league immediately, banned for a full season, and if reinstated, will begin at the lowest tier available.​</p>

    <p>The RFL Commissioner and the RFL reserve the right to remove, ban, or relegate any player at any time that they see fit.</p>

</div>
