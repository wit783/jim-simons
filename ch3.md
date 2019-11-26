CHAPTER THREE
Getting fired can be a good thing.

You just don’t want to make a habit of it.

Jim Simons

Weeks after leaving Stony Brook University’s expansive, tree-lined campus in the early summer of 1978, Simons found himself just a few miles down the road, yet a world away.

Simons sat in a storefront office in the back of a dreary strip mall. He was next to a women’s clothing boutique, two doors down from a pizza joint, and across from the tiny, one-story Stony Brook train station. His space, built for a retail establishment, had beige wallpaper, a single computer terminal, and spotty phone service. From his window, Simons could barely see the aptly named Sheep Pasture Road, an indication of how quickly he had gone from broadly admired to entirely obscure.

The odds weren’t in favor of a forty-year-old mathematician embarking on his fourth career, hoping to revolutionize the centuries-old world of investing. Indeed, Simons appeared closer to retirement than any sort of historic breakthrough. His graying hair was long and stringy, almost to his shoulders. A slight paunch made him look even more like an aging professor out of step with modern finance.

Until then, Simons had dabbled in investing but hadn’t demonstrated any special talent. Sure, the stake Simons and his father had in Charlie Freifeld’s investment partnership had grown to about a million dollars after Freifeld correctly anticipated a surge in sugar prices, but disaster had barely been averted. Just weeks after Freifeld dumped the group’s holdings, sugar prices had plummeted. Neither Freifeld nor Simons had anticipated the fall. They had simply agreed to cash out if they ever scored a substantial profit.

“It was incredible,” Simons says, “but it was completely lucky.”1

Somehow, Simons was bursting with self-confidence. He had conquered mathematics, figured out code-breaking, and built a world-class university department. Now he was sure he could master financial speculation, partly because he had developed a special insight into how financial markets operated. Some investors and academics saw the markets’ zigs and zags as random, arguing that all possible information was already baked into prices, so only news, which is impossible to predict, could push prices higher or lower. Others believed that price shifts reflected efforts by investors to react to and predict economic and corporate news, efforts that sometimes bore fruit.

Simons came from a different world and enjoyed a unique perspective. He was accustomed to scrutinizing large data sets and detecting order where others saw randomness. Scientists and mathematicians are trained to dig below the surface of the chaotic, natural world to search for unexpected simplicity, structure, and even beauty. The emerging patterns and regularities are what constitute the laws of science.2

Simons concluded that markets didn’t always react in explainable or rational ways to news or other events, making it difficult to rely on traditional research, savvy, and insight. Yet, financial prices did seem to feature at least some defined patterns, no matter how chaotic markets appeared, much as the apparent randomness of weather patterns can mask identifiable trends.

It looks like there’s some structure here, Simons thought.

He just had to find it.

Simons decided to treat financial markets like any other chaotic system. Just as physicists pore over vast quantities of data and build elegant models to identify laws in nature, Simons would build mathematical models to identify order in financial markets. His approach bore similarities to the strategy he had developed years earlier at the Institute for Defense Analyses, when he and his colleagues wrote the research paper that determined that markets existed in various hidden states that could be identified with mathematical models. Now Simons would test the approach in real life.

There must be some way to model this, he thought.

Simons named his new investment company Monemetrics, combining the words “money” and “econometrics” to indicate that he would use math to analyze financial data and score trading gains. At the IDA, Simons had built computer models to spot “signals” hidden in the noise of the communications of the United States’ enemies. At Stony Brook, he had identified, courted, and managed talented mathematicians. Now Simons would hire a team of big brains to pore through the market’s data to identify trends and develop mathematical formulas to profit from them.

Simons wasn’t sure where to start. All he knew was that currency markets had become unshackled, presenting profit potential. He did have an ideal partner in mind for his fledgling firm: Leonard Baum, one of the co-authors of the IDA research paper and a mathematician who had spent time discerning hidden states and making short-term predictions in chaotic environments. Simons just had to convince Baum to risk his career on Simons’s radical, unproven approach.

=
Lenny Baum was born in 1931, the son of immigrants who had fled Russia for Brooklyn to escape rampant poverty and anti-Semitism. At the age of thirteen, Lenny’s father, Morris, began work on the floor of a hat factory, where he eventually became the manager and owner. As a teenager, Lenny was six feet tall with a barrel chest, his high school’s top sprinter and a member of its tennis team, though his delicate hands suggested someone more comfortable turning the pages of a textbook than competing on a court.

One day, while visiting nearby Brighton Beach with friends, Lenny spotted a vivacious and attractive young woman chatting with friends. Julia Lieberman had come with her family to the United States at the age of five from a small village in Czechoslovakia, clutching her favorite doll as they escaped the Nazis on the last boat from Europe in 1941. Once in New York, Julia’s father, Louis, spent months unsuccessfully searching for a job. Discouraged, he decided to show up at a local factory and try to blend in with its workers. Louis proved such a tireless laborer that he was added to the payroll. Later, Louis operated a laundromat in the family’s small row house, but the Lieberman family would always struggle financially.

Lenny and Julia fell in love and eventually married and moved to Boston, where Lenny attended Harvard University, graduating in 1953 and then earning a PhD in mathematics. Julia finished fourth in her class at Boston University before obtaining a master of arts in education and history at Harvard. After joining the IDA in Princeton, Baum was even more successful breaking code than Simons, receiving credit for some of the unit’s most important, and still classified, achievements.

“Lenny and some others were definitely higher than Jim in what we in management used to call ‘lifeboat order,’” Lee Neuwirth says.

Balding and bearded, Baum pursued math research while juggling government assignments, just like Simons. Over the course of several summers in the late 1960s, Baum and Lloyd Welch, an information theorist working down the hall, developed an algorithm to analyze Markov chains, which are sequences of events in which the probability of what happens next depends only on the current state, not past events. In a Markov chain, it is impossible to predict future steps with certainty, yet one can observe the chain to make educated guesses about possible outcomes. Baseball can be seen as a Markov game. If a batter has three balls and two strikes, the order in which they came and the number of fouls in between don’t matter. If the next pitch is a strike, the batter is out.

A hidden Markov process is one in which the chain of events is governed by unknown, underlying parameters or variables. One sees the results of the chain but not the “states” that help explain the progression of the chain. Those not acquainted with baseball might throw their hands up when receiving updates of the number of runs scored each inning—one run in this inning, six in another, with no obvious pattern or explanation. Some investors liken financial markets, speech recognition patterns, and other complex chains of events to hidden Markov models.

The Baum-Welch algorithm provided a way to estimate probabilities and parameters within these complex sequences with little more information than the output of the processes. For the baseball game, the Baum-Welch algorithm might enable even someone with no understanding of the sport to guess the game situations that produced the scores. If there was a sudden jump from two runs to five runs, for example, Baum-Welch might suggest the probability that a three-run home run had just been hit rather than a bases-loaded triple. The algorithm would allow someone to infer a sense of the sport’s rules from the distribution of scores, even as the full rules remained hidden.

“The Baum-Welch algorithm gets you closer to the final answer by giving you better probabilities,” Welch explains.

Baum usually minimized the importance of his accomplishment. Today, though, Baum’s algorithm, which allows a computer to teach itself states and probabilities, is seen as one of the twentieth century’s notable advances in machine learning, paving the way for breakthroughs affecting the lives of millions in fields from genomics to weather prediction. Baum-Welch enabled the first effective speech recognition system and even Google’s search engine.

For all of the acclaim Baum-Welch brought Lenny Baum, most of the hundreds of other papers he wrote were classified, which grated on Julia. She came to believe her husband was getting neither the recognition nor the pay he deserved. The Baum children had little idea what their father was up to. The few times they asked, he told them his work was classified. Baum did tell them what he wasn’t working on.

“We’re not making bombs,” he reassured his daughter Stefi one day, as controversy about the Vietnam War flared.

Unlike Simons, Baum was a homebody who spent little time socializing, playing poker, or interacting with others. Most evenings, he sat quietly on a faux-leopard-skin couch in his family’s modest Princeton home, scribbling on a yellow pad with a pencil. When Baum ran into a particularly challenging problem, he’d stop, gaze far into the distance, and ponder. Baum fit the stereotype of an absentminded professor—once, he came to work with half a beard, explaining that he had become distracted thinking about mathematics while shaving.

During his tenure at the IDA, Baum had noticed his eyesight deteriorating. Doctors eventually determined he suffered from cone-rod dystrophy, a disorder affecting the cone cells on the retina. Baum found it difficult to engage in activities requiring visual clarity, such as tennis. Once, at the net, a ball hit Baum square in the head. The same thing happened in Ping-Pong; his clear blue eyes would see the ball for a moment and then lose it, forcing Baum to drop the sports.

He remained surprisingly upbeat, focusing on pleasures he still could enjoy, such as walking two miles a day near the Princeton campus. Grateful he could read and write, despite the decline of his fine, sharp, straight-ahead vision, Baum maintained an unbreakable optimism.

“Let the problem be,” Baum liked to say, usually with a smile, when his kids came to him with concerns. “It will solve itself.”

After Simons left the IDA to lead Stony Brook’s mathematics department, however, the Baum family began to detect uncharacteristic frustration in their patriarch. When Baum broke a Russian code and identified a spy but the FBI proved too slow arresting the suspect, he expressed irritation. Baum became discouraged about his unit’s future, writing an internal memo emphasizing the need for better recruitment.

“It is obvious that the loss of Simons is serious for us, both because we need him mathematically and because of the manner of his departure,” Baum wrote, referring to Simons’s firing. “During the period of seven months when Simons supposedly wasn’t working on defense material, he, in fact, did more work on defense projects than some of our members have done in the last few years.”3

One day in 1977, Simons reached out to Baum, asking if he would spend a day at Monemetrics’ office on Long Island helping Simons set up a trading system to speculate on currencies. Baum chuckled at the invitation. He didn’t know much about trading, despite his earlier theoretical paper with Simons, and cared so little about investing that he left the family’s portfolio entirely in his wife’s hands. Nonetheless, Baum agreed to spend some time assisting Simons, as a favor to his old friend.

At the office, Simons set charts depicting the daily closing values of various major currencies in front of Baum, as if he was presenting him with a mathematical problem. Scrutinizing the data, Baum quickly determined that, over stretches of time, some currencies, especially the Japanese yen, seemed to move in steady, straight lines. Perhaps Simons was right, Baum thought, there did seem to be some inherent structure in the markets. Baum hypothesized that the yen’s steady climb might be due to the Japanese government, under pressure from foreign nations, intervening to buy the currency “in precise Japanese manner” to make Japanese exports a bit less competitive. Either way, Baum agreed with Simons that a mathematical model might be developed to map out and ride trends in various currencies.

Baum began working with Simons once a week. By 1979, Baum, then forty-eight years old, was immersed in trading, just as Simons had hoped. A top chess player in college, Baum felt he had discovered a new game to test his mental faculties. He received a one-year leave of absence from the IDA and moved his family to Long Island and a rented, three-bedroom Victorian house lined with tall bookcases. Because his eyesight had worsened, Julia drove her husband back and forth to Simons’s office each day.

“Let’s see if we can make a model,” Simons told him, as they prepared to focus on markets.

It didn’t take Baum long to develop an algorithm directing Monemetrics to buy currencies if they moved a certain level below their recent trend line and sell if they veered too far above it. It was a simple piece of work, but Baum seemed on the right path, instilling confidence in Simons.

“Once I got Lenny involved, I could see the possibilities of building models,” Simons later said.4

Simons called some friends, including Jimmy Mayer and Edmundo Esquenazi, asking if they would invest in his new fund. Simons showed them the same charts he had presented Baum, wowing them with how much he and Baum would have made had they used their mathematics-focused trading strategy over the course of the previous several years.

“He came with this chart and impressed us with the possibilities,” Mayer says.

Simons failed to raise the $4 million he was shooting for, but he came close enough to begin his fund, which also held his own money. He called his new investment fund Limroy, an amalgam of Lord Jim, the protagonist of the Joseph Conrad novel of the same name, and the Royal Bank of Bermuda, which handled the new company’s money transfers so that it could glean the advantages, tax-related and otherwise, of being located offshore. The name blended high-finance with a character known for wrestling with ideals of honor and morality, a fitting choice for someone who long had one foot in the world of business and another in mathematics and academia.

Simons decided Limroy would be a hedge fund, a loosely defined term for private investment partnerships that manage money for wealthy individuals and institutions and pursue a variety of strategies, including trying to hedge, or protect, themselves from losses in the overall market.

Monemetrics would invest a bit of money for Simons, testing strategies in a variety of markets. If the tactics looked profitable, Simons would place the same trades in Limroy, which was much bigger and would invest for outsiders as well as for Simons. Baum would share in the 25 percent cut the firm claimed from all its trading profits.

Simons hoped he and Baum could make big money relying on a trading style that combined mathematical models, complicated charts, and a heavy dose of human intuition. Baum became so certain their approach would work, and so hooked on investing, that he quit the IDA to work full-time with Simons.

To make sure he and Baum were on the right track, Simons asked James Ax, his prized recruit at Stony Brook, to come by and check out their strategies. Like Baum a year or so earlier, Ax knew little about investing and cared even less. He immediately understood what his former colleagues were trying to accomplish, though, and became convinced they were onto something special. Not only could Baum’s algorithm succeed in currencies, Ax argued, but similar predictive models could be developed to trade commodities, such as wheat, soybeans, and crude oil. Hearing that, Simons persuaded Ax to leave academia, setting him up with his own trading account. Now Simons was really excited. He had two of the most acclaimed mathematicians working with him to unlock the secrets of the markets and enough cash to support their efforts.

A year or two earlier, Baum couldn’t stop thinking about math; now it was trading that occupied his mind. Lying on a beach with his family one morning during the summer of 1979, Baum mulled the extended weakness in the value of the British pound. At the time, the conventional wisdom was that the currency could only fall in value. One expert who advised Simons and Baum on their trading made so much selling pounds that he named his son Sterling.

Relaxing on the beach that morning, Baum sat straight up, overcome with excitement. He was convinced a buying opportunity was at hand. Baum raced to the office, telling Simons that Margaret Thatcher, Britain’s new prime minister, was keeping the currency at unsustainably low levels.

“Thatcher is sitting on the pound,” Baum said. “She can’t hold it down much longer.”

Baum said they needed to buy pounds, but Simons was amused, rather than swayed, by Baum’s sudden conviction.

“Lenny, it’s too bad you didn’t come in earlier,” Simons responded, smiling. “Thatcher stood up. . . . The pound just rose five cents.”

That morning, it turned out, Thatcher had decided to let the pound rise in price. Baum was unfazed.

“That’s nothing!” he insisted. “It’s going to go up fifty cents—maybe more!”5

Baum was right. He and Simons kept buying British pounds, and the currency kept soaring. They followed that move with accurate predictions for the Japanese yen, West German deutsche mark, and Swiss franc, gains that had the South American investors calling Simons with congratulations and encouragement as the fund grew by tens of millions of dollars.

Fellow mathematicians still scratched their heads about why Simons had discarded a promising career to sit in a makeshift office trading currency contracts. They were just as stunned that Baum and Ax had joined him. Even Simons’s father seemed disappointed. In 1979, at a bar mitzvah party for Simons’s son Nathaniel, Matty Simons told a Stony Brook mathematician, “I liked to say, ‘My son, the professor,’ not ‘My son, the businessman.’”

Simons spent little time looking back. After racking up early currency winnings, Simons amended Limroy’s charter to allow it to trade US Treasury bond futures contracts as well as commodities. He and Baum—who now had their own, separate investment accounts—assembled a small team to build sophisticated models that might identify profitable trades in currency, commodity, and bond markets.

Simons was having a blast exploring his lifelong passion for financial speculation while trying to solve markets, perhaps the greatest challenge he had encountered. Besides, he joked, his wife Marilyn at last could “hang out with people and know what they were talking about.”6

The fun wouldn’t last.

=
Searching for someone to program his computers, Simons heard about a nineteen-year-old on the verge of getting kicked out of the California Institute of Technology. Greg Hullender was sharp and creative, but he had trouble focusing on his schoolwork and did poorly in many of his courses. Later in life, he would be diagnosed with attention-deficit disorder. At the time, Hullender was frustrated by his struggles, as were the school’s administrators. The last straw came when he was caught running an unauthorized, high-stakes trading operation out of his dorm room. Friends pooled their cash and handed it to Hullender, who purchased stock options before a market rally in 1978, turning $200 into $2,000 in a matter of days. Soon, everyone in the dorm wanted in on the operation, throwing money at Hullender, who began repackaging stock options purchased through a brokerage account at Merrill Lynch and reselling them to eager students.

“It was like my own stock exchange,” Hullender says, with pride.

Merrill Lynch officials weren’t amused by his ingenuity. Citing Hullender for violating the terms of his account, the brokerage pulled the plug on his venture and the school kicked him out. Sitting in his dorm room, waiting to be expelled, Hullender was startled by a seven a.m. phone call from Simons. Simons had heard about Hullender’s unlicensed trading operation through a Caltech grad student and was impressed by Hullender’s understanding of financial markets, as well as his moxie. Simons offered Hullender a salary of $9,000 a year, as well as a share of his firm’s profits, to come to New York to program Limroy’s trades.

With a round, cherubic face, shaggy brown hair, and a boyish smile, Hullender looked like a teenager heading off to summer camp, not someone cut out for a cross-country trip to join an unknown trading operation. Rail-thin with thick, oversize glasses, Hullender kept pens in his front pocket, along with a brown case for his spectacles, a look that made him appear especially guileless.

Hullender hadn’t met Simons or Baum and was wary of the job offer.

“Jim’s firm sounded like the shadiest thing in the world,” he says.

The young man didn’t hesitate to accept Simons’s offer, however.

“I was in my dorm room waiting to get kicked out—it’s not like I had a lot of options.”

Hullender moved to Long Island, staying with Simons and his family for several weeks until he rented a room in a nearby Stony Brook dormitory. The young man didn’t have a driver’s license, so Simons lent him a bicycle to get to work. At the office, Simons, wearing his usual open-collared cotton shirt and loafers, gave Hullender a tutorial on how he approached trading. Currency markets are affected by the actions of governments and others, Simons told him, and his firm hoped to develop detailed, step-by-step algorithms to identify “trends that result from hidden actors influencing the market,” not unlike what Simons did at the IDA to break enemy code.

Hullender began by writing a program to track the new firm’s results. Within six months, Hullender’s figures showed disturbing losses—Simons’s shift to bond trading had gone awry. Clients kept calling, but now they were asking why they were losing so much money, rather than extending congratulations.

Simons seemed to take the downturn hard, growing more anxious as the losses increased. On one especially rough day, Hullender found his boss lying supine on a couch in his office. Hullender sensed Simons wanted to open up to him, perhaps even make some kind of confession.

“Sometimes I look at this and feel I’m just some guy who doesn’t really know what he’s doing,” Simons said.

Hullender was startled. Until that moment, Simons’s self-confidence seemed boundless. Now he appeared to be second-guessing his decision to ditch mathematics to try to beat the market. Still on the couch, as if in a therapist’s office, Simons told Hullender about Lord Jim, which centers on failure and redemption. Simons had been fascinated with Jim, a character who had a high opinion of himself and yearned for glory but failed miserably in a test of courage, condemning himself to a life filled with shame.

Simons sat up straight and turned to Hullender.

“He had a really good death, though,” he said. “Jim died nobly.”

Wait, is Simons contemplating suicide?

Hullender worried about his boss—and about his own future. Hullender realized he had no money, was alone on the East Coast, and had a boss on a couch talking about death. Hullender tried reassuring Simons, but the conversation turned awkward.

In the following days, Simons emerged from his funk, more determined than ever to build a high-tech trading system guided by algorithms, or step-by-step computer instructions, rather than human judgment. Until then, Simons and Baum had relied on crude trading models, as well as their own instincts, an approach that had left Simons in crisis. He sat down with Howard Morgan, a technology expert he’d hired to invest in stocks, and shared a new goal: building a sophisticated trading system fully dependent on preset algorithms that might even be automated.

“I don’t want to have to worry about the market every minute. I want models that will make money while I sleep,” Simons said. “A pure system without humans interfering.”

The technology for a fully automated system wasn’t there yet, Simons realized, but he wanted to try some more sophisticated methods. He suspected he’d need reams of historic data, so his computers could search for persistent and repeating price patterns across a large swath of time. Simons bought stacks of books from the World Bank and elsewhere, along with reels of magnetic tape from various commodity exchanges, each packed with commodity, bond, and currency prices going back decades, some to before World War II. This was ancient stuff that almost no one cared about, but Simons had a hunch it might prove valuable.

Hullender’s five-foot-tall, blue-and-white PDP-11/60 computer couldn’t read some of the older data Simons was amassing because its formatting was outdated, so Hullender surreptitiously carried the reels to the nearby headquarters of Grumman Aerospace, where his friend Stan worked. Around midnight, when things slowed down at the defense contractor, Stan let Hullender fire up a supercomputer and spend hours converting the reels so they could be read on Simons’s computer. As the reels spun, the friends caught up over coffee.

To gather additional data, Simons had a staffer travel to lower Manhattan to visit the Federal Reserve office to painstakingly record interest-rate histories and other information not yet available electronically. For more recent pricing data, Simons tasked his former Stony Brook secretary and new office manager, Carole Alberghine, with recording the closing prices of major currencies. Each morning, Alberghine would go through the Wall Street Journal and then climb on sofas and chairs in the firm’s library room to update various figures on graph paper hanging from the ceiling and taped to the walls. (The arrangement worked until Alberghine toppled from her perch, pinching a nerve and suffering permanent injury, after which Simons enlisted a younger woman to scale the couches and update the numbers.)

Simons recruited his sister-in-law and others to input the prices into the database Hullender created to track prices and test various trading strategies based on both mathematical insights and the intuitions of Simons, Baum, and others. Many of the tactics they tried focused on various momentum strategies, but they also looked for potential correlations between commodities. If a currency went down three days in a row, what were the odds of it going down a fourth day? Do gold prices lead silver prices? Might wheat prices predict gold and other commodity prices? Simons even explored whether natural phenomena affected prices. Hullender and the team often came up empty, unable to prove reliable correlations, but Simons pushed them to keep searching.

“There’s a pattern here; there has to be a pattern,” Simons insisted.

Eventually, the group developed a system that could dictate trades for various commodity, bond, and currency markets. The office’s single computer wasn’t powerful enough to incorporate all the data, but it could identify a few reliable correlations.

The trading system had live hogs as a component, so Simons named it his “Piggy Basket.” The group built it to digest masses of data and make trading recommendations using the tools of linear algebra. The Piggy Basket produced a row of numbers. The sequence “0.5, 0.3, 0.2,” for example, would signify that the currency portfolio should be 50 percent yen, 30 percent deutsche marks, and 20 percent Swiss francs. After the Piggy Basket churned out its recommendations for about forty different futures contracts, a staffer would get in touch with the firm’s broker and deliver buy-and-sell instructions based on those proportions. The system produced automated trade recommendations, rather than automated trades, but it was the best Simons could do at the time.

For a few months, the Piggy Basket scored big profits, trading about $1 million of Monemetrics’ money. The team generally held its positions for a day or so, then sold them. Encouraged by the early results, Simons transferred several million dollars of additional cash from the Limroy account into the model, scoring even larger gains.

Then, something unexpected happened. The computerized system developed an unusual appetite for potatoes, shifting two-thirds of its cash into futures contracts on the New York Mercantile Exchange that represented millions of pounds of Maine potatoes. One day, Simons got a call from unhappy regulators at the Commodity Futures Trading Commission: Monemetrics was close to cornering the global market for these potatoes, they said, with some alarm.

Simons had to stifle a giggle. Yes, the regulators were grilling him, but they had to realize Simons hadn’t meant to accumulate so many potatoes; he couldn’t even understand why his computer system was buying so many of them. Surely, the CFTC would understand that.

“They think we’re trying to corner the market on spuds!” he told Hullender, with some amusement, after hanging up the phone.

The regulators somehow missed the humor in Simons’s misadventure. They closed out his potato positions, costing Simons and his investors millions of dollars. Soon, he and Baum had lost confidence in their system. They could see the Piggy Basket’s trades and were aware when it made and lost money, but Simons and Baum weren’t sure why the model was making its trading decisions. Maybe a computerized trading model wasn’t the way to go, after all, they decided.

In 1980, Hullender quit to go back to school. Leaving college prematurely weighed on him, and he was ashamed he couldn’t help Simons make more progress on his computerized trading system. Hullender couldn’t understand the math Simons and Baum were using, and he was lonely and miserable. Weeks earlier, he had revealed to colleagues that he was gay. They tried to make him comfortable, but the young man felt increasingly out of place.

“I just felt I had a better chance meeting someone compatible in California,” says Hullender, who eventually earned his degree and became a machine-learning specialist for Amazon and Microsoft. “Some things are more important than money.”

=
With Hullender gone and the Piggy Basket malfunctioning, Simons and Baum drifted from predictive mathematical models to a more traditional trading style. They began looking for undervalued investments while reacting to market-moving news, investing $30 million in various markets.

Simons thought it might help if they could get their hands on news from Europe before their rivals, so he hired a Parisian studying at Stony Brook to read an obscure French financial newsletter and translate it before others had a chance. Simons also consulted with an economist named Alan Greenspan, who later would become Federal Reserve chair. At one point, Simons set up a red phone in his office that rang whenever urgent financial news broke, so he and Baum could enter trades before others. Sometimes the phone rang and they were nowhere to be found, sending new office manager Penny Alberghine, Carole’s sister-in-law, racing to find them, be it in a local restaurant or shop or even the men’s room, where she’d pound on the door to get their attention.

“Come back in!” Alberghine screamed once. “Wheat’s down thirty points!”

Simons’s cheeky, irreverent sense of humor put his team at ease. He’d tease Alberghine about her thick New York accent, and she’d mock the remains of his Boston inflection. Once, Simons became elated when he received an especially high interest rate for money the firm held in a bank account.

“Investors are getting eleven and seven-fucking-eighths!” he exclaimed.

When a young employee gasped at his blue language, Simons flashed a grin.

“I know—that is an impressive rate!”

A few times a week, Marilyn came by to visit, usually with their baby, Nicholas. Other times, Barbara checked in on her ex-husband. Other employees’ spouses and children also wandered around the office. Each afternoon, the team met for tea in the library, where Simons, Baum, and others discussed the latest news and debated the direction of the economy. Simons also hosted staffers on his yacht, The Lord Jim, docked in nearby Port Jefferson.

Most days, Simons sat in his office, wearing jeans and a golf shirt, staring at his computer screen, developing new trades—reading the news and predicting where markets were going, like most everyone else. When he was especially engrossed in thought, Simons would hold a cigarette in one hand and chew on his cheek. Baum, in a smaller, nearby office, trading his own account, favored raggedy sweaters, wrinkled trousers, and worn Hush Puppies shoes. To compensate for his worsening eyesight, he hunched close to his computer, trying to ignore the smoke wafting through the office from Simons’s cigarettes.

Their traditional trading approach was going so well that, when the boutique next door closed, Simons rented the space and punched through the adjoining wall. The new space was filled with offices for new hires, including an economist and others who provided expert intelligence and made their own trades, helping to boost returns. At the same time, Simons was developing a new passion: backing promising technology companies, including an electronic dictionary company called Franklin Electronic Publishers, which developed the first hand-held computer.

In 1982, Simons changed Monemetrics’ name to Renaissance Technologies Corporation, reflecting his developing interest in these upstart companies. Simons came to see himself as a venture capitalist as much as a trader. He spent much of the week working in an office in New York City, where he interacted with his hedge fund’s investors while also dealing with his tech companies.

Simons also took time to care for his children, one of whom needed extra attention. Paul, Simons’s second child with Barbara, had been born with a rare hereditary condition called ectodermal dysplasia. Paul’s skin, hair, and sweat glands didn’t develop properly, he was short for his age, and his teeth were few and misshapen. To cope with the resulting insecurities, Paul asked his parents to buy him stylish and popular clothing in the hopes of fitting in with his grade-school peers.

Paul’s challenges weighed on Simons, who sometimes drove Paul to Trenton, New Jersey, where a pediatric dentist made cosmetic improvements to Paul’s teeth. Later, a New York dentist fitted Paul with a complete set of implants, improving his self-esteem.

Baum was fine with Simons working from the New York office, dealing with his outside investments, and tending to family matters. Baum didn’t need much help. He was making so much money trading various currencies using intuition and instinct that pursuing a systematic, “quantitative” style of trading seemed a waste of time. Building formulas was difficult and time-consuming, and the gains figured to be steady but never spectacular. By contrast, quickly digesting the office’s news ticker, studying newspaper articles, and analyzing geopolitical events seemed exciting and far more profitable.

“Why do I need to develop those models?” Baum asked his daughter Stefi. “It’s so much easier making millions in the market than finding mathematical proof.”

Simons respected Baum too much to tell him how to trade. Besides, Baum was on a roll, and the firm’s computer firepower was limited, making any kind of automated system likely impossible to implement.

Baum liked to pore over economic and other data, close the door to his office, and lie back on his green sofa, reflecting for long periods on his next market move.

“He’d lose track of time,” Penny Alberghine says. “He was a bit spacey.”

When Baum emerged, he usually placed buy orders. An optimist by nature, Baum liked to purchase investments and sit on them until they rose, no matter how long it took. Courage was needed to hold on to investment positions, Baum told friends, and he was proud he didn’t buckle when others grew weak in the knees.

“If I don’t have a reason for doing something, I leave things as they are and do nothing,” he wrote to family members, explaining his trading tactics.

“Dad’s theory was buy low and hold on forever,” Stefi says.

The strategy enabled Baum to ride out market turbulence and rack up more than $43 million in profits between July 1979 and March 1982, nearly double his original stake from Simons. In the latter year, Baum grew so bullish about stocks that he insisted on missing the firm’s annual outing on Simons’s yacht, preferring to monitor the market and buy more stock futures. Around noon, when Baum grudgingly joined his colleagues, Simons asked why he looked so glum.

“I got half of what I wanted,” Baum said. “Then I had to come to this lunch.”

Baum probably should have stayed in the office. He had correctly identified that year’s historic bottoming out of the US stock market. As stocks soared and his profits piled up, Lenny and Julia purchased a six-bedroom, turn-of-the-century home on Long Island Sound. Julia still drove an old Cadillac, but she no longer worried about money. The trading life had a less salutary impact on her husband, despite his mounting gains. Once relaxed and upbeat, Baum turned serious and intense, fielding calls from Simons and others well into the evening as they debated how to react to news of the day.

“He was like a different person,” Stefi recalls.

=
Baum’s penchant for holding on to investments eventually caused a rift with Simons. The tension started back in the fall of 1979, when they each purchased gold-futures contracts at around $250 an ounce. Late that year, the Iranian government took fifty-two American diplomats and citizens hostage and Russia invaded Afghanistan to support that country’s communist regime. The resulting geopolitical jitters pushed gold and silver prices higher. Visitors to the Long Island office watched as Baum, normally quiet and introspective, stood, exuberantly cheering gold higher. Simons sat nearby, smiling.

By January 1980, gold and silver prices were soaring. When gold topped $700 in a frenzied two-week period, Simons dumped his position, locking in millions of dollars of profits. As usual, Baum couldn’t bear to sell. One day, Simons was speaking with a friend who mentioned that his wife, a jeweler, was rifling through his closet, removing gold cuff links and tie clips to sell.

“Are you going broke or something?” Simons asked with concern.

“No—she can cut the line to sell,” the friend responded.

“There’s a line to sell gold?”

The friend explained that people around the country were queuing up to sell jewelry, taking advantage of surging prices. Simons turned scared; if the supply of gold was swelling, that could crush prices.

Back in the office, Simons gave Baum an order.

“Lenny, sell right now.”

“No—the trend will continue.”

“Sell the fucking gold, Lenny!”

Baum ignored Simons, driving him crazy. Baum was sitting on more than $10 million of profits, gold had skyrocketed past $800 an ounce, and he was sure more gains were ahead.

“Jim nagged me,” Baum later told his family. “But I couldn’t find any specific reason or news for action, so I did nothing.”

Finally, on January 18, Simons dialed the firm’s broker and pressed the phone to Baum’s ear.

“Tell him you’re selling, Lenny!”

“Alright, alright,” Baum grumbled.

Within months, gold had raced past $865 an ounce, and Baum was bitterly complaining that Simons had cost him serious money. Then the bubble burst; just a few months later, gold was under $500 an ounce.

A bit later, Baum discovered a native of Colombia who worked at the brokerage firm E. F. Hutton and claimed to have insights into the coffee-futures market. When the Colombian predicted higher prices, Baum and Simons built some of the largest positions in the entire market. Almost immediately, coffee prices dropped 10 percent, costing them millions. Once again, Simons dumped his holdings but Baum couldn’t bear selling. Eventually, Baum lost so much money he had to ask Simons to get rid of the coffee investment for him; he was unable to do it himself. Baum later described the episode as “the dumbest thing I ever did in this business.”

Baum’s eternal optimism was beginning to wear on Simons.

“He had the buy-low part, but he didn’t always have the sell-high part,” Simons later said.7

By 1983, Baum and his family had moved to Bermuda, where they enjoyed the island’s idyllic weather and favorable tax laws. The island’s beauty reinforced Baum’s upbeat nature and bullish instincts. US inflation seemed under control, and Federal Reserve Chair Paul Volcker predicted a decline in interest rates, so Baum purchased tens of millions of dollars of US bonds, an ideal investment for that kind of environment.

But panic selling overcame the bond market in the late spring of 1984 amid surging bond issuance by the administration of President Ronald Reagan and rapid US economic growth. As his losses grew, Baum maintained his typical equanimity, but Simons feared the troubles could take the firm down.

“Lighten up, Lenny. Don’t be stubborn,” Simons said.

Baum’s losses kept growing. A huge wager that the yen would continue to appreciate also backfired, placing Baum under even more pressure.

“This cannot continue!” Baum said one day, staring at his computer screen.

When the value of Baum’s investment positions had plummeted 40 percent, it triggered an automatic clause in his agreement with Simons, forcing Simons to sell all of Baum’s holdings and unwind their trading affiliation, a sad denouement to a decades-long relationship between the esteemed mathematicians.

Ultimately, Baum proved prescient. In subsequent years, both interest rates and inflation tumbled, rewarding bond investors. By then, Baum was trading for himself, and he and Julia had returned to Princeton. The years with Simons had been filled with such stress that Baum rarely enjoyed a full night’s sleep. Now he was rested and had time to return to mathematics. As he grew older, Baum focused on prime numbers and an unsolved and well-known problem, the Riemann hypothesis. For fun, he traveled the country competing in Go tournaments, memorizing the board or standing over it to compensate for his ever-declining eyesight.

In his eighties, Baum enjoyed walking two miles from his home to Witherspoon Street, near Princeton University’s campus, stopping to smell budding flowers along the way. Passing drivers sometimes slowed to offer assistance to the slow, well-dressed older gentleman, but he always declined the help. Baum would spend hours sitting in the sun at coffee shops, striking up conversations with strangers. Family members sometimes found him gently comforting homesick undergraduates. In the summer of 2017, weeks after finalizing his latest mathematics paper, Baum passed away at the age of eighty-six. His children published the paper posthumously.

=
Baum’s losses in the 1984 trading debacle left deep scars on Simons. He halted his firm’s trading and held disgruntled investors at bay. Once staffers eagerly greeted the frequent calls from Simons’s friends, who asked, “How are we doing?” Now that the fund was losing millions of dollars daily, Simons instituted a new rule with clients—no performance results until the end of each month.

The losses had been so upsetting that Simons contemplated giving up trading to focus on his expanding technology businesses. Simons gave clients the opportunity to withdraw their money. Most showed faith, hoping Simons could figure out a way to improve the results, but Simons himself was racked with self-doubt.

The setback was “stomach-wrenching,” he told a friend. “There’s no rhyme or reason.”

Simons had to find a different approach.
