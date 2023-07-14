<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneOneTwo, oneOneThree, oneOneFour, oneTwo, oneTwoOne, oneTwoTwo, oneThree, oneThreeOne, oneThreeTwo, oneThreeThree, oneFour, oneFourOne, oneFourTwo, oneFourThree, oneFive, oneFiveOne;
    let two, twoOne, twoTwo, twoThree, twoThreeOne, twoThreeTwo, twoFour, twoFourOne;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;
    let eight;
    let nine;
    let ten;
    let eleven;
    let twelve;
    let thirteen;
    let fourteen;
    let fifteen;
    let sixteen;

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
        margin-left: 4em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    .subBlock {
        margin-left: 2.4em;
    }
    .subBlock5 {
        margin-left: 4.8em;
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
    <h1 class="noUnderscore">Hall of Shamers Dynasty League: A Rulebook</h1>
    <p>Welcome to the Hall of Shamers Dynasty League. Please read the bylaws below.</p>
    <p>The purpose of these bylaws is to (1) ensure a fair and fun league for all owners, (2) ensure the long term viability of the league. If a rule is not explicitly stated, the Co-Commissioners will be responsible for interpreting these criteria and new rules will be voted on and subsequently documented in these bylaws, with each team having two votes: One per co-manager and two if the team is managed solo. If this document disagrees with league site settings, site settings will prevail until corrected.</p>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Section 1: Owner Conduct & Responsibilities</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneOne)}>1.1 Responsibilities</h4>
            <!--h5 class="noUnderscore clickable" on:click={() => goToSection(oneOneOne)}>1.1.1 Position Maximums</h5-->
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneTwo)}>1.2 Conduct</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneThree)}>1.3 Activity Requirements</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneFour)}>1.4 Anti-Competitive Behaviour</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneFive)}>1.5 Violations</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Section 2: Teams, Ownership, and Replacement</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Section 3: League Governance</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: League Platforms</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: Rosters</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Free Agency and FAAB</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: Trades</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(eight)}>Section 8: Startup Draft</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(nine)}>Section 9: Annual Rookie Draft</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(ten)}>Section 10: Fees, Payouts, and Travelling Trophy</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(eleven)}>Section 11: Regular Season</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(twelve)}>Section 12: Playoffs</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(thirteen)}>Section 13: Scoring</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(fourteen)}>Section 14: Rules Changes</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(fifteen)}>Section 15: Calendar</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(sixteen)}>Section 16: Changelog</h3>
    
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
        <li>If an owner does not intend to return for the next season, their trades must be approved by a co-commissioner prior to being completed.</li>
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


    <h2 class="sectionHeading" bind:this={two}>Section 2 Teams, Ownership, and Replacement</h2>
    
    <h3 bind:this={twoOne}>2.1</h3>
    <p>The League will be comprised of 12 teams.</p>

    <h3 bind:this={twoTwo}>2.2</h3>
    <p>For each franchise, the team owner(s) must choose a team name</p>
    
    <h3 bind:this={twoThree}>2.3</h3>
    <p>Leaving the League:</p>

    <h4 bind:this={twoThreeOne}>2.3.1</h4>
    <div class="subBlock">
        <p>An owner may choose to retire “in good standing” between Week 17 and the 2 weeks prior to the Rookie Draft. When this is announced, the owner will be prevented from making transactions. The owner may be permitted to rejoin the league if there is a vacancy in the future.</p>
    </div>

    <h4 bind:this={twoThreeTwo}>2.3.2</h4>
    <div class="subBlock">
        <p>An owner who leaves the league under any other conditions (“ban") shall be prevented from making transactions and shall not be permitted to rejoin the league in the future.</p>
    </div>

    <h3 bind:this={twoFour}>2.4</h3>
    <p>Replacement Process</p>
    <h4 bind:this={twoFourOne}>2.4.1</h4>
    <div class="subBlock">
        <p>Owner vacancies will be posted on the message board. The list of potential owners shall be voted upon by league members and the vote winner shall be awarded the vacancy (pending payment of dues).</p>
    </div>


    <h2 class="sectionHeading" bind:this={three}>Section 3 League Governance</h2>
    <h3 bind:this={threeOne}>3.1</h3>	
    <p>Jesse Kennedy and Bob Deziel are the Co-Commissioners.<p>
    <h4>3.1.1</h4>
    <div class="subBlock">
        <p>The Co-Commissioners will act in good faith and at all times in the best interest of the league to maintain a fun, fair, and competitive environment.</p>
    </div>
    <h4>3.1.2</h4>
    <div class="subBlock">
        <p>In the rare instance that a situation arises that is not covered by the bylaws, the Co-Commissioners has the right to rule on the issue in the best interest of the league and these rulings are final, binding, and cannot be appealed.</p>
    </div>
    <h4>3.1.3</h4>
    <div class="subBlock">
        <p>The Co-Commissioners explicitly shall not make executive decisions that alter what is set in the bylaws for:</p>
    </div>
        <h5>3.1.3.1</h5>
        <div class="subBlock5">
            <p>League payout settings</p>
        </div>
        <h5>3.1.3.2</h5>
        <div class="subBlock5">
            <p>League scoring settings [aside from interpreting existing rules and ruling on uncertainties] </p>
        </div>
        <h5>3.1.3.3</h5>
        <div class="subBlock5">
            <p>League roster settings (aside from interpretation of existing rules and ruling on uncertainties) </p>
        </div>
    <h4>3.1.4</h4>
    <div class="subBlock">
        <p>The Co-Commissioners shall be empowered to complete the following:</p>
    </div>
        <h5>3.1.4.1</h5>
        <div class="subBlock5">
            <p>Exercise executive decision rights in all cases of uncertainty for situations occurring in the current year and/or requiring immediate decisions </p>
        </div>
        <h5>3.1.4.2</h5>
        <div class="subBlock5">
            <p>Set lineups and perform team/roster moves for owners by request (in case of emergency, subject to the Co-Commissioners’ availability) </p>
        </div>
        <h5>3.1.4.3</h5>
        <div class="subBlock5">
            <p>Finalize league calendar dates and times, and ensure calendar is updated and followed </p>
        </div>
        <h5>3.1.4.4</h5>
        <div class="subBlock5">
            <p>Collect league dues, enforce payment deadlines, and facilitate payouts as per this document </p>
        </div>
        <h5>3.1.4.5</h5>
        <div class="subBlock5">
            <p>Ensure that actions that require dues to be paid are completed only if dues are up to date </p>
        </div>
        <h5>3.1.4.6</h5>
        <div class="subBlock5">
            <p>Investigate inactivity, rules violations, and owner misconduct, and assign sanctions at their discretion </p>
            <ul>
            <li>Inactivity and misconduct sanctions can be appealed within 48 hours of assigned sanction </li>
            </ul>
        </div>
        <h5>3.1.4.7</h5>
        <div class="subBlock5">
            <p>Apply sanctions at his discretion, from the following list of sanctions - in order of severity:</p>
            <ol>
            <li>Retroactive cancellation of trades and forfeits declared for any affected games</li>
            <li>Suspension of transaction rights for a specified period</li>
            <li>Fine of $100 FAAB</li>
            <li>Fine of $250 FAAB</li>
            <li>Forfeiture of draft picks</li>
            <li> Removal of owner from league (aka Ban)</li>
            </ol>
            <p>*All FAAB fines shall be taken from the current season’s budget if possible - if not possible the following season’s budget will be reduced. If the owner is booted from the league, all "following-season" penalties shall be removed.</p>
        </div>

    <h2 class="sectionHeading" bind:this={four}>Section 4 League Platforms</h2>
    <h3>4.1</h3>
    <p>League will be hosted on Sleeper</p>
    <h3>4.2</h3>	
    <p>Communications will be hosted on Facebook Messenger and the Facebook Group</p>    
    <h3>4.3</h3>	
    <p>All official announcements shall be posted the Facebook Group Dynasty for Dummies.</p>
    <h3>4.4</h3>	
    <p>League fees will be paid to one of either Co-Commissioner (Bob or Jesse)</p>

    <h2 class="sectionHeading" bind:this={five}>Section 5 Rosters</h2>
    <h3>5.1</h3>
    <p>Roster Limits</p>
    <h4>5.1.1</h4>
    <div class="subBlock">
        <p>During the NFL regular season, there shall be a hard maximum of 28 players on the active roster, with a maximum of two kickers per team.</p>
    </div>
    <h4>5.1.2</h4>
    <div class="subBlock">
        <p>Starting the day of the rookie draft, the roster limit will expand to 33 spaces to accommodate picks.</p>
    </div>
    <h3>5.2</h3>
    <p>Two IR spots shall be allocated to each team, and shall be used as follows </p>
    <h4>5.2.1</h4>
    <div class="subBlock">
        <p>Must be listed as (IR) or (I) on Sleeper</p>
    </div>
    <h4>5.2.2</h4>
    <div class="subBlock">
        <p>If the player no longer qualifies under rule he must be moved to the active roster or the owner shall be prevented from setting a valid lineup. </p>
    </div>
    <h3>5.3</h3>
    <p>Five Taxi Squad spots shall be allocated to each team and shall be used as follows: </p>
    <h4>5.3.1</h4>
    <div class="subBlock">
        <p>Any player that has been in the NFL for less than three years shall be permitted to be on the Taxi Squad </p>
    </div>
    <h4>5.3.2</h4>
    <div class="subBlock">
        <p>Once an owner promotes a player from the Taxi Squad, they, any other team, shall not be allowed to demote him again. </p>
    </div>


    <h2 class="sectionHeading" bind:this={six}>Section 6 Free Agency and FAAB</h2>
    <h3>6.1</h3>
    <p>All dropped players shall go onto waivers. Owners can blind bid on these players from their Free Agency Auction Budget (FAAB).</p>
    <h4>6.1.1</h4>
    <div class="subBlock">
        <p>Each owner starts the season with $1000 to spend on Free Agents. The minimum increment of bid is $1, and the minimum bid is $0 </p>
    </div>
    <h4>6.1.2</h4>
    <div class="subBlock">
        <p>At each waiver process time, the highest bid shall receive the player if there is roster room. If there is a tie, the played with the highest waiver priority shall receive the player. The winning bid shall be deducted from the budget. </p>
    </div>
    <h4>6.1.3</h4>
    <div class="subBlock">
        <p>The FAAB Budget resets every year at the start of DFL regular season (Preseason Week 2).</p>
    </div>
    <h3>6.2</h3>
    <p>Processing Times </p>
    <h4>6.2.1</h4>
    <div class="subBlock">
        <p>During the DFL regular season (Preseason Week 2 to the end of Week 17), waivers are processed weekly (Tuesday at 9 PM Atlantic Time) and after each waiver processing free agents shall be available via Open Free Agency (First-Come-First-Serve transactions).</p>
    </div>
    <h4>6.2.2</h4>
    <div class="subBlock">
        <p>During the DFL offseason (Week 17 to kickoff preseason Week 2) waivers are processed weekly (Wednesday 12am), and players will be locked after each waiver processing.</p>
    </div> 

 <h2 class="sectionHeading" bind:this={seven}>Section 7 Trades</h2>
    <h3>7.1</h3>
    <p>Players, FAAB, and two-year-advance (i.e. 2022 and 2023 picks in 2021) rookie picks are available for trade.</p>
    <h3>7.2</h3>
    <p>Trades shall only be binding when completed on the Sleeper platform, and shall be manually processed by a Co-Commissioner within 24 hours.</p>
    <h3>7.3</h3>
    <p>If a trade has been offered or accepted in error, the owner making the error must notify the Co-Commissioners and the other team immediately (i.e. within 10 minutes of the trade acceptance) to request that the trade be voided. Trades may only be voided due to legitimate error that is reported in a timely manner - trades may not be voided due to buyer’s remorse, seller’s remorse, or failure to perform due diligence. The Co-Commissioners reserve the right to allow a trade to stand if the error is not deemed credible.</p>
    <h3>7.4</h3>
    <p>Owners must abide strictly by roster limits prior to any trades being processed.</p>
    <h3>7.5</h3>
    <p>Trades may be vetoed by a unanimous vote from Co-Commissioners on grounds of collusion or anti-competitive conduct, and trades may be retroactively voided if anti-competitive conduct is discovered. Owners involved may be required to forfeit games. The rationale for a veto shall be publicly documented and published to the official league chat.</p>
    <h3>7.6</h3>
    <p>Trade Deadline</p>
    <h4>7.6.1</h4>
    <div class="subBlock">
        <p>Trades shall be excluded between the ending of the last game of week 12 and the ending of the final game of week 17. Trades are permitted at all other times.</p>
    </div>


 <h2 class="sectionHeading" bind:this={eight}>Section 8 Startup Draft</h2>
    <h3>8.1</h3>
    <p>The league will initially select players via a 30 round startup draft.</p>

 <h2 class="sectionHeading" bind:this={nine}>Section 9 Annual Rookie Draft</h2>
    <h3>9.1</h3>
    <p>Beginning year two of the DFL, each Rookie Draft shall take place no later than one month after the NFL rookie draft.</p>
    <h3>9.2</h3>
    <p>Draft order will be set in the following manner:</p>
    <h4>9.2.1</h4>
    <div class="subBlock">
        <p>The four six place teams (teams 7-12) in the final league standings after completion of the playoffs will have the first six positions in the draft, with their positions being determined via a draft lottery, with team 12 receiving 8ballots, team 11 6 ballots, team 10 receiving 4 ballots, team 9 receiving 3 ballots, team 8 receiving 2 ballots, and team 7 receiving 1 ballot. </p>
    </div>
    <h5>9.2.1.1</h5>
    <div class="subBlock5">
        <p>In the lottery, team 12 cannot receive worse than the 1.04 position for the rookie draft, and team 11 cannot receive worse than the 1.05 position in the rookie draft.</p>
    </div>
     <h5>9.2.1.2</h5>
    <div class="subBlock5">
        <p>Team standings for teams 7-12 will be determined by their maximum season theoretical points for as determined by Sleeper, with the team with the fewest maximum theoretical points for receiving 12th place in the league.</p>
    </div>
    <h4>9.2.2</h4>
    <div class="subBlock">
        <p>The final six teams will draft in reverse order according to the position that they finished after completion of the playoffs, with the exception of teams that lose in the first round of the playoffs, whose order in the draft will be determined by their maximum season theoretical points for as determined by Sleeper., with the team with the fewest maximum theoretical points for receiving 6th place standing, and the team with the most maximum theoretical points for receiving 5th place standing</p>
    </div>
    <h3>9.3</h3>
    <p>Draft will be conducted on Sleeper through email.</p>
    <h4>9.3.1</h4>
    <div class="subBlock">
        <p>Draft will consist of 6 rounds, done linearly (not snake).</p>
    </div>
    <h4>9.3.2</h4>
    <div class="subBlock">
        <p>Each pick is allotted a 12 hour draft clock</p>
    </div>
    <h5>9.3.2.1</h5>
    <div class="subBlock5">
        <p>Draft clock will start immediately following the previous pick </p>
    </div>
    <h4>9.3.3</h4>
    <div class="subBlock">
        <p>Failure to pick in the allotted time frame will result in the highest ranked player being drafted. </p>
    </div>
    <h4>9.3.4</h4>
    <div class="subBlock">
        <p>In the unlikely event a disruption occurs during the email draft with adverse results to any owner or team, the Co-Commissioners reserve the right to pause, modify, or otherwise alter the draft in such a way that corrects the adverse effect and promotes fairness and integrity of the league. Under no circumstances shall the Co-Commissioners or any owner alter the draft results or process so as to grant an unfair advantage to any owner. </p>
    </div>
    <h3>9.4</h3>
    <p>Prior to the Rookie Draft every roster will get a 6 man roster increase accommodate the new picks (31 total players). The roster must be reduced to 25 plus the five man taxi squad two weeks prior to the first game of the NFL regular season in order to submit a valid lineup for week 1. </p>


 <h2 class="sectionHeading" bind:this={ten}>Section 10 Fees, Payouts, and Travelling Trophy</h2>
    <h3>10.1</h3>
    <p>FEES </p>
    <h4>10.1.1</h4>
    <div class="subBlock">
        <p>ANNUAL FEE: The annual fee for the league shall be $100 paid to the co-commissioner responsible for fees and league dues, due on or before the NFL draft of the successive years.</p>
    </div>
    <h4>10.1.2</h4>
    <div class="subBlock">
        <p>TOTAL: The total fees collected for the league shall be $1200 per year.</p>
    </div>
    <h4>10.1.3</h4>
    <div class="subBlock">
        <p>If a replacement owner has their league fees waived then an equal percentage will be subtracted from all three payouts. </p>
    </div>
    <h3>10.2</h3>
    <p>PAYOUTS</p>
    <h4>10.2.1</h4>
    <div class="subBlock">
        <p>THIRD PLACE PRIZE ($100)</p>
    </div>
    <h4>10.2.2</h4>
    <div class="subBlock">
        <p>SECOND PLACE PRIZE ($250)</p>
    </div>
    <h4>10.2.3</h4>
    <div class="subBlock">
        <p>FIRST PLACE PRIZE ($850)</p>
    </div>
    <h3>10.3</h3>
    <p>All payouts are to be done by the Co-Commissioners according to the above listing within 7 days of the championship game</p>
    <h3>10.4</h3>
    <p>Traveling Trophy</p>
    <h4>10.4.1</h4>
    <div class="subBlock">
        <p>The traveling trophy will be delivered to the League Champion(s) which the champion(s) will need to have engraved.</p>
    </div>


 <h2 class="sectionHeading" bind:this={eleven}>Section 11 Regular Season</h2>
    <h3>11.1</h3>
    <p>The season is comprised of 14 head to head matchups (NFL Weeks 1-14)</p>
    <h3>11.2</h3>
    <p>Schedule will be built using the Sleeper schedule creator. Errors in scheduling should be brought up immediately. The Co-Commissioners reserves the right to make corrections as needed.</p>


 <h2 class="sectionHeading" bind:this={twelve}>Section 12 Playoffs</h2>
    <h3>12.1</h3>
    <p>Playoff will take place Weeks 15-17</p>
    <h3>12.2</h3>
    <p>The playoffs shall be comprised of the six teams with the highest winning percentage.</p>
    <h4>12.2.1</h4>
    <div class="subBlock">
        <p>If two or more teams have the same winning percentage, the following tie-breaker rules will be enforced in this order:</p>
    </div>
    <h5>12.2.1.1</h5>
    <div class="subBlock5">
        <p>The team with the higher regular season point total.	</p>
    </div>
    <h5>12.2.1.2</h5>
    <div class="subBlock5">
        <p>The team with the better head-to-head record.</p>
    </div>
    <h3>12.3</h3>
    <p>The Playoff eligible Teams shall be seeded one (1) through six (6) based on overall winning percentage, total points scored, and head-to-head match-ups won.</p>
    <h4>12.3.1</h4>
    <div class="subBlock">
        <p>The Teams seeded one (1) and two (2) will have a bye week (Week 15)</p>
    </div>
    <h4>12.3.2</h4>
    <div class="subBlock">
        <p>The remaining teams will play based on seeding (3) vs (6) and (4) vs (5)</p>
    </div>
    <h4>12.3.3</h4>
    <div class="subBlock">
        <p>Each subsequent week of matchups will be determined by highest seed vs lowest seed. </p>
    </div>



 <h2 class="sectionHeading" bind:this={thirteen}>Section 13 Scoring</h2>
    <h3>13.1</h3>
    <p>0.1 points per rushing yard or receiving yard, 0.04 points per passing yard</p>
    <h3>13.2</h3>
    <p>6 points per touchdown, with the exception of passing touchdowns, which are worth 4 points.</p>
    <h3>13.3</h3>
    <p>0.5 points per reception </p>
    <h4>13.3.1</h4>
    <div class="subBlock">
        <p>Starting in 2024, 1 point per reception for TE </p>
    </div>
    <h3>13.4</h3>
    <p>-2 points per interception, -2 points per lost fumble for offensive players</p>
    <h3>13.5</h3>
    <p>Remaining scoring events not explicitly stated in the bylaws can be found on Sleeper</p>
    <h3>13.6</h3>
    <p>Scoring Lineups: QB, Q/W/R/T, WR, WR, WR, RB, RB, TE, W/R/T, W/R/T, K</p>
    <h3>13.7</h3>
    <p>Sleeper will apply official scoring corrections without exception, and changes will automatically take effect and may not be appealed (scoring, game outcomes, or otherwise).</p>
    <h3>13.8</h3>
    <p>Sleeper will determine player positions and make changes at their discretion.</p>


 <h2 class="sectionHeading" bind:this={fourteen}>Section 14 Rule Changes</h2>
    <h3>14.1</h3>
    <p>The rules for each season shall be finalized by the NFL Super Bowl of each year and updated on Sleeper.</p>
    <h3>14.2</h3>
    <p>Each owner may submit rule changes at any time prior to NFL playoffs. Proposed rule changes may not take effect until after the Super Bowl. A proposed rule change may not be voted on more than once per year.</p>
    <h3>14.3</h3>
    <p>No rule change shall reasonably disadvantage any owner without their consent - if such a rule is passed, the disadvantaged owner may appeal to the Co-Commissioners to postpone the implementation of such a rule by one or more full seasons.</p>
    <h3>14.4</h3>
    <p>All proposals must be posted to the Facebook Group. Discussion of rules is highly encouraged. </p>
    <h3>14.5</h3>
    <p>Polls will operate based on popular vote</p>
    <h4>14.5.1</h4>
    <div class="subBlock">
        <p>All polls must have the current rule as an option for voting</p>
    </div>



<h2 class="sectionHeading" bind:this={fifteen}>Section 15 Calendar</h2>
    <ul>
    <li><strong>NFL Draft</strong> - League Fees Due</li>
    <li><strong>One Month After NFL Draft</strong> - Roster increase and Rookie Draft</li>
    <li><strong>NFL Preseason Week 2</strong> - Start of DFL regular season, once weekly FAAB then regular free agency, FAAB reset, and roster cuts</li>
    <li><strong>NFL Week 1</strong> - Week 1 of DFL matchups</li>
    <li><strong>NFL Week 15</strong> - Start of DFL playoffs</li>
    <li><strong>NFL Week 18</strong> - End of DFL regular season and once weekly FAAB / no free agency</li>
    <li><strong>NFL Playoffs</strong> - Proposed rule changes due and start of voting</li>    
    <li><strong>NFL Superbowl</strong> - All approved rule changes take effect</li>
    </ul>

<h2 class="sectionHeading" bind:this={sixteen}>Section 16 Changelog</h2>
    <p>August 8th 2021 – Final 2021 pre-season version of Bylaws accepted by members</p>
    <p>September 26th 2021 - Clarifications made to how the rookie draft is to proceed. Section 9.2.1.1 added, stating:</p>
    <div class="subBlock">
        <p>9.2.1.1 Team standings for teams 7-12 will be determined by their win / loss record throughout the regular season, and if two teams share the same record the tie breaker will be the total number of points scored throughout the season.</p>
    </div>
    <p>And this section added to part 9.2.1, stating:</p>
    <div class="subBlock">
        <p>with their positions being determined via a draft lottery, with team 12 receiving 40% of the ballots, team 11 receiving 30% of the ballots, team 10 receiving 20% of the ballots, and team 9 receiving 10% of the ballots.</p>
    </div>
    <p>May 3rd 2022 – Outcomes of rule change votes:</p>
    <ul>
    <li>Two votes per team (one for co-managers, two for solo managers)</li>
    <li>Trade deadline will be after the last game of week 12</li>
    <li>Waiver system stays as is (free agency after waivers clear)</li>
    <li>Rookie draft position changes – playoff teams stay the same, non-playoff teams in the draft lottery based off theoretical maximum points over the season (as determined by Sleeper)</li>
    <li>Teams 7 and 8 remain out of the draft lottery – Only teams 9 – 12 are in the lottery</li>
    <li>Keeping once-a-year FAAB reset</li>
    <li>Changing waiver times from 4 AM (ADT) to 9 PT ADT – Whether that will be Tuesday or Wednesday evening is yet to be determined</li>
    <li>Winners will now pay for their own of the trophy</li>
    <li>We’ll be adding a set date (week) for the draft lottery</li>
    </ul>
    <p>April 6th 2023  – Rule change votes to be implemented:</p>
    <ul>
    <li>New rule for active players in the line up was accepted</li>
    <li>Draft lottery for non-playoff teams has been expanded to include all non-playoff teams, with a future vote determining ballot distribution</li>
    <li>Fumbles that result in a recovery by the offense are now scored at 0, fumbles lost still result in -2 for the fumbling player</li>
    <li>Adding in TE premium in 2024 </li>
    <li>Seeding of 1.07 and 1.08 determined by their regular season finish (by Max PF, just like we do with draft picks 1.01 - 1.06 lotto draft)</li>
    <li>Keeping roster size at current 28, not reducing it to 25</li>
    </ul>
 

</div>
