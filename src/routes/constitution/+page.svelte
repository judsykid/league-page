<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneOneTwo, oneOneThree, oneOneFour, oneTwo, oneTwoOne, oneTwoTwo, oneThree, oneThreeOne, oneThreeTwo, oneThreeThree, oneFour, oneFourOne, oneFourTwo, oneFourThree, oneFive, oneFiveOne;
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
        text-decoration: underline;
        margin-left: 6em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    .subBlock {
        margin-left: 2.4em;
    }
    .subBlock5 {
        margin-left: 6.4em;
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
    <h1 class="noUnderscore">LEGENDS LEAGUE CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Section 1: Owner Conduct & Responsibilities</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneOne)}>1.1 Responsibilities</h4>
            <!--h5 class="noUnderscore clickable" on:click={() => goToSection(oneOneOne)}>1.1.1 Position Maximums</h5-->
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneTwo)}>1.2 Conduct</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneThree)}>1.3 Activity Requirements</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneFour)}>1.4 Anti-Competitive Behaviour</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneFive)}>1.5 Violations</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Section 2: Drafting</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoOne)}>2.1 Draft Order</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoTwo)}>2.2 Rookie Drafts</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoThree)}>2.3 Draft Day Trades</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Section 3: Scoring System</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeOne)}>3.1 Voting on Scoring System</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: Postseason</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourOne)}>4.1 Playoffs</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourTwo)}>4.2 Playoff Tiebreakers</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: Tanking Policy</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.1 League Tanking Policy</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Replacing Managers</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixOne)}>6.1 Removing Managers</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>6.2 Replacing Managers</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixThree)}>6.3 Replacement Incentive</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: League Finances</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenOne)}>7.1 League Dues</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>7.2 Payout</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixThree)}>7.3 Raising Dues</h4>
    
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1 Owner Conduct & Responsibilities</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>1.1 Responsibilities</h3>
    
    
        <h4 bind:this={oneOneOne}>1.1.1</h4>
        <div class="subBlock">
        <p>Owners are responsible for knowing and following the rules and deadlines set out in these bylaws.</p>   
        </div>
        <h4 bind:this={oneOneTwo}>1.1.2</h4>
        <div class="subBlock">
        <p>Owners are responsible for participating in all required league functions and activities, whether they occur during the season or the offseason.</p>    
        </div>
        <h4 bind:this={oneOneThree}>1.1.3</h4>
        <div class="subBlock">
        <p>Owners are responsible for notifying the Co-Commissioners if they will be away for an extended period of time.</p>    
        </div>
        <h4 bind:this={oneOneFour}>1.1.4</h4>
        <div class="subBlock">
        <p>Owners are responsible for responding to emails and private messages from the Co-Commissioners and other league members in a timely manner.</p>    
        </div>

        <h3 class="subSectionHeading" bind:this={oneTwo}>1.2 Conduct</h3>
  
    <h4 bind:this={oneTwoOne}>1.2.1</h4>
    <div class="subBlock">
        <p>Trash talking and shit-posting are actively encouraged.</p>
    </div>

    <h4 bind:this={oneTwoTwo}>1.2.2</h4>
    <div class="subBlock">
        <p>The Co-Commissioners shall be the moderators of all chat channels.</p>
    </div>

    <h3 bind:this={oneThree}>1.3 Activity Requirements</h3>

    <h4 bind:this={oneThreeOne}>1.3.1</h4>
    <div class="subBlock">
        <p>Trade inquiries sent by DFL must be responded to within a certain time limit, as set out below:</p>
        <ol>
        <li>During season: 48 hours</li>
        <li>During offseason: 7 days</li>
        <li>The Co-Commissioners may extend the time limit by request or in extenuating circumstances, at their discretion.</li>
        <li>An owner may respond to a trade by rejecting/countering/accepting through the software platform.</li>
        </ol>
    </div>

    
    <h4 bind:this={oneThreeTwo}>1.3.2</h4>
    <div class="subBlock">
        <p>Lineups must be set weekly during the season, including playoffs, with the exception of bye-week playoffs.</p>
    </div>
    <h5>1.3.2.1</h5>
    <div class="subBlock5">
        <p>With the exception of kicker, if a team does not have an active player available to be played in a position a replacement player does not need to be acquired to fill the position.</p>
    </div>


    <h4 bind:this={oneThreeThree}>1.3.3</h4>
    <div class="subBlock">
        <p>Failure to meet activity requirements will result in warnings, sanctions, or removal from the league. </p>
    </div>

    <h3 bind:this={oneFour}>1.4 Anti-Competitive Behaviour</h3>

    <h4 bind:this={oneFourOne}>1.4.1</h4>
    <div class="subBlock">
        <p>Anticompetitive conduct is defined as owners or teams engaging in conduct that prevents, reduces, or otherwise negatively affects the natural competition and well-being of the league. Such conduct is subject to sanctions.</p>
        <ol>
        <li>During season: 48 hours</li>
        <li>During offseason: 7 days</li>
        <li>The Co-Commissioners may extend the time limit by request or in extenuating circumstances, at their discretion.</li>
        <li>An owner may respond to a trade by rejecting/countering/accepting through the software platform.</li>
        </ol>
    </div>

    <h4 bind:this={oneFourTwo}>1.4.2</h4>
    <div class="subBlock">
        <p>The following actions are strictly prohibited: 
    </div>
    <h5>1.4.2.1</h5>
    <div class="subBlock5">
        <p>Anti-Competitive Trades</p>
        <ol>
        <li>Owners may not make trades that result in worsening their own team in order to stock another team playing a third team they want or need to lose.</li>
        <li>1.4.2.1.2. If an owner does not intend to return for the next season, their trades must be approved by a co-commissioner prior to being completed.</li>
        </ol>
    </div>
    <h5>1.4.2.2</h5>
    <div class="subBlock5">     
        <p>Collusion</p>
        <ol>
        <li>Collusion is defined as two or more owners making arrangements and/or acting in concert to influence the results of league activities such as game outcomes, draft standing or player availability</li>
        <li>Any unsportsmanlike conduct coordinated between two or more owners is considered to be collusion, as is teams trading to consolidate better players on one team and/or agreeing to share payouts by acting in concert.</li>
        </ol>
    </div>
    <h5>1.4.2.3</h5>
    <div class="subBlock5">     
        <p>Roster Dumping</p>
        <ol>
        <li>An owner who, without good reason, cuts players from their team who are obviously valuable is subject to sanctions.</li>
        <li>It is understood that teams can and will drop “borderline” players from their rosters, but dropping obvious fantasy starters or large amounts of average players in an attempt to increase draft position, make players available to others by way of collusion, or sabotage the integrity of the league, shall not be tolerated.</li>
        </ol>
    </div>

    <h4 bind:this={oneFourThree}>1.4.3</h4>
    <div class="subBlock">
        <p>Tanking</p>
    </div>
    <h5>1.4.3.1</h5>
    <div class="subBlock5">
        <p>Tanking is permitted but an owner must submit a valid lineup weekly.</p>
    </div>

    <h3 bind:this={oneFive}>1.5 Violations</h3>

    <h4 bind:this={oneFiveOne}>1.5.1</h4>
    <div class="subBlock">
        <p>Owners may report rule/bylaw violations to the Co-Commissioners for investigation - they can do so anonymously if they so choose. The Co-Commissioners will investigate and may assess sanctions or forfeits.</p>
    </div>
    <h5>1.5.1.1</h5>
    <div class="subBlock5">
        <p>Official reports must be submitted for review in the week that the violation took place, prior to the subsequent kickoff.</p>
    <ol>
        <li>Sanctions or forfeits in response to violations will be issued within the same week, time permitting, but no later than 48 hours from the report.</li>
        <li>The Co-Commissioners reserve the right to enforce sanctions outside the one week window for egregious violations that harm the competitive balance of the league. </li>
        </ol>
    </div>


    <h2 class="sectionHeading" bind:this={two}>Section 2 Drafting</h2>
    
    <h3 bind:this={twoOne}>2.1 Draft Order</h3>
    <p>The draft order each year will be a linear draft in reverse order of the previous year’s regular season standings.</p>

    <h3 bind:this={twoTwo}>2.2 Rookie Drafts</h3>
    <p>Rokkie drafts will consist of 3 round of drafting, with 5 minutes alotted for each pick. To make room for the incoming players, benches will be expanded by (5) spots. These spots will be removed in mid-August, at which point you will need to have cut the necessary players.</p>
    <p>Any spots not filled during the draft, can be filled immediately afterwards from the waiver wire.</p>
    
    <h3 bind:this={twoThree}>2.3 Draft Day Trades</h3>
    <p>If a trade is being made during the draft, one or both parties can alert the commissioner to pause the draft to allow for extra time to negotiate the trade.</p>
    
    <h2 class="sectionHeading" bind:this={three}>Section 3 Scoring System</h2>

    <h3 bind:this={threeOne}>3.1 Scoring System</h3>
    <p>The league scoring system breakdown is listed on the Sleeper fantasy app (for the most part, it follows typical .5PPR Scoring). The scoring system will never change without a majority league vote.</p>
    
    <h2 class="sectionHeading" bind:this={four}>Section 4 Postseason</h2>
    
    <h3 bind:this={fourOne}>4.1 Playoffs</h3>
    <p>At the end of the season 6 teams will make the playoffs. The first round of playoffs will commence in week 15. Each team that wins their division and the 4 wild card teams that finish with the best records, will receive a playoff berth. The 2 teams that win their division will receive a bye week in the first round of the playoffs. Each playoff matchup will only last one week and the winner will advance. Week 18 will not be used.</p>
    
    <h3 bind:this={fourTwo}>4.2 Seeding Tiebreakers</h3>
    <p>If two teams finish with the same record the tiebreakers will go as followed:</p>

    <ol>
        <li>Points For</li>
        <li>Head 2 Head Record</li>
        <li>Division Record</li>
        <li>Total Points Against</li>
        <li>Coin Flip</li>
        <li>Duel to the death</li>
    </ol>

    <h2 class="sectionHeading" bind:this={five}>Section 5 Tanking Policy</h2>
    
    <h3 bind:this={fiveOne}>5.1 League Tanking Policy</h3>
    <p>No team may intentionally leave starting roster spots empty. Any evidence of intentionally leaving roster spots empty in order to improve your draft position may be subject to punishment, including but not limited to the forfeiture of draft selections.</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6 Replacing Managers</h2>
    
    <h3 bind:this={sixOne}>6.1 Removing Managers</h3>
    <p>Short of continuously failing to set a valid lineup, or confirmed collusion, no manager can be removed against their will. Participation, through the league chat, trade offers, and the waiver wire, is strongly encouraged but generally grounds for removal.</p>
    
    <h3 bind:this={sixTwo}>6.2 Replacing Managers</h3>
    <p>When a manager needs to be replaced, the commisiooners will try to find a suitable candidate with some connection to at least a portion of the existing managers. Priority will be placed on managers who are eager to take on a dynasty commitment and will be very active within the league.</p>
    
    <h3 bind:this={sixThree}>6.3 Replacement Incentive</h3>
    <p>In the event that a manager chooses to quit the league or is removed by a comissioner, an incoming manager is offered a 50% reductioon on their first year buy-in.</p>

    <h2 class="sectionHeading" bind:this={seven}>Section 7 League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>
    <p>League dues are set at {dues}$. Dues are collected through <a href="https://www.leaguesafe.com/league/3949641">LeagueSafe</a> and collection will be sent out no later than the first of August. All managers must be fully paid up before the start of regular season. In the event that a manager fails to pay before the deadline, a 10% penalty will be addd to their payment and will go towards the payouts at the end of the year.</p>
    
    <h3 bind:this={sevenTwo}>7.2 Payout</h3>
    <p>League payout is structured as follows:</p>
    <ul>
        <li>1st place: {dues * 8}$</li>
        <li>2nd place: {dues * 3}$</li>
        <li>3rd place: {dues}$</li>
    </ul>
    <p>In the event that a manager was fined due to late payment, their extra fee will be added to the winner's payout. Similarly, if new managers come into the league and the payout is smaller, the difference will come out of the winner's prize.</p>
    
    <h3 bind:this={sevenThree}>7.3 Raising Dues</h3>
    <p>A ⅔ majority vote is required in order to raise league dues. In the event that a manager is no longer financially comfortable with the buyin, finding a co-manager to split the cost is reccomended.</p>

</div>
