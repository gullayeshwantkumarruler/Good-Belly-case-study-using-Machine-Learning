# Good-Belly-case-study-using-Machine-Learning

GoodBelly: Using Statistics to Justify the Marketing
Expense

case  
August 1, 2012

Published by WDI Publishing, a division of the William Davidson Institute (WDI) at the University of Michigan.
©2012 Hyun-Soo Ahn and Caroline Dickerson. This case was written by Hyun-Soo Ahn, Associate Professor of Operations and Management
Science at the Ross School of Business at the University of Michigan, and Caroline Dickerson, a Ross MBA. This case was prepared as
the basis for class discussion rather than to illustrate effective or ineffective handling of an administrative situation. Company data
were disguised to protect proprietary information and enable class discussion.
GoodBelly was a new line of probiotic juice products produced by Colorado-based NextFoods Inc.
NextFoods was founded by Steve Demos, the founder of WhiteWave Inc., and Todd Beckman, a former vice
president at WhiteWave Foods Company—the US’s largest producer of soy-based products, including Silk
Soymilk. Since its first product launch in January of 2008, GoodBelly products were now on the shelves of
nationwide retailers such as Whole Foods Market Inc. and Safeway Inc.
Probiotics are live bacteria that are beneficial to the host organism. Probiotics and other pathogens
enter the bloodstream through the stomach lining. Over 100 trillion bacteria and other microorganisms
live in the intestines, and the influx of good
bacteria can aid digestion and support the
immune system. By 2008, the global market for
probiotic and prebiotic food and beverages was
substantial, at $15.4 billion, and still growing.
Probiotic products grew between 5% and 30%
in 2008—exceptional growth considering
that the overall food market grew only 1-2%.
There were hundreds of probiotic products on
the market, from yogurt to pizza to chocolate.
Perhaps the most notable brand was Activia,
a family of yogurts produced by The Dannon
Company Inc. Activia contained a proprietary
strain of Bifidobacterium called Bifidobacterium
animalis DN 173 010, which sparked an increase
in probiotic awareness in the US.
GoodBelly products were organic juice-based drinks (see Figure 1). While most probiotic products were
dairy-based, GoodBelly’s products were dairy-free, soy-free, and vegan. All GoodBelly products used live and
active cultures of a proprietary probiotic strain called Lactobacillus plantarum299v (Lp299v), which had
been used in Europe for more than 15 years and thoroughly tested in over 17 research trials.
Figure 1
GoodBelly Products

Source: GoodBelly.com. 31 March 2012.
For the exclusive use of S. Colla, 2023.

This document is authorized for use only by Sebastian Colla in Applied Statistics 23 taught by Weijia Peng, Sacred Heart University from Jan 2023 to Jun 2023.

2

GoodBelly: Using Statistics to Justify the Marketing Expense  

Promotional Programs
Initially, GoodBelly had the challenge of raising product awareness, particularly about the benefits of
probiotics and the great taste. As a recent start-up in the fairly new probiotic market, GoodBelly did not have
the funding to place nationwide advertisements. It instead allocated much of its small marketing budget to
in-store demonstrations. GoodBelly believed that the key to selling products was through customer trials.
Demonstrations provided the perfect opportunity to meet consumers, educate them about probiotics, and
get them to taste the product.
The company’s in-store demo program was launched in November of 2009. The program originally
targeted all stores that carried GoodBelly products. However, after a few months of trials, management
noticed that exposure at smaller stores was very limited and that demonstrations were only effective in
stores with sufficient foot traffic. As a result, management modified the program to focus only on Whole
Foods stores, which represented approximately 75% of sales in 2009.
During in-store demonstrations, GoodBelly representatives handed out product samples. The
representatives were people hired for part-time work through local service outsourcing agencies. Before
conducting demonstrations, representatives received training so that they could answer all questions about
probiotics and GoodBelly products. For a typical demonstration, a representative arrived at a specified store,
set up a table (preferably near the product in the store), and arranged the product on the table. For the next
three hours, he or she then distributed samples, informed consumers about the product, and offered coupons
to inspire purchase. Later, the representative wrote up a report that included: the store, date and time, what
products sold, how much product was used as samples, and the questions asked by customers. The report
was then faxed to GoodBelly managers.
Another promotional program
involved competitions among the five
GoodBelly sales representatives for the
most endcap displays. The endcap is
the hub at the end of an aisle—one
of the store’s most popular locations.
Sales representatives competed for
the highest number of stores they
could convince to place GoodBelly’s
products at the endcap. The winning

sales representative received a big-
screen television. There was also a

competition among Whole Foods stores
for the best-decorated endcap—an
example of which can be seen in
Figure 2. The winning store received
GoodBelly sweatshirts, cases of product
for the employees, and gift cards.
Justifying the Expense
Due to limited marketing resources, management was pressured to cut any marketing expense that
did not directly contribute to GoodBelly’s results. By July of 2010, several concerns were raised within
the company about the effectiveness of the in-store demo program. Some questioned whether the demos

Figure 2

GoodBelly Endcap Displays

Source: GoodBelly company documents. 2012.
For the exclusive use of S. Colla, 2023.

This document is authorized for use only by Sebastian Colla in Applied Statistics 23 taught by Weijia Peng, Sacred Heart University from Jan 2023 to Jun 2023.

3

GoodBelly: Using Statistics to Justify the Marketing Expense  

boosted sales at all, while others were concerned that any boost was only temporary and that sales would
revert to normal levels shortly afterward. Some executives questioned whether the increase in sales volume
could justify the associated costs. Similar concerns were raised for the endcap competition, even though
management was convinced that the competition at least raised morale among sales representatives.
At the senior manager meeting in July of 2010, GoodBelly management expressed concerns about the
promotional budget and asked Marty Wellbeing, GoodBelly’s marketing manager, to justify the demo and
endcap activities. Wellbeing strongly believed that, unless he could convince management of the programs’
efficacy, his department would be hit for budget reduction.
Wellbeing returned to his computer after the meeting. He pored over the sales and promotion spreadsheet
from the last few months. Though he knew the information in Exhibit 1, he could not immediately decipher
the answers that would save his department’s budget. Wellbeing recognized that statistics could be used
to help his case, but was afraid that none of his staff members were perfectly suited for the job—all the
marketing staffers were former field sales consultants. He then remembered that GoodBelly’s new intern
Caroline Dickerson had taken a statistics course. He asked Dickerson to assess the GoodBelly sales spreadsheet
and identify, if any, the impact of the in-store demos and endcap promotions. He cautioned Dickerson that
several senior managers, most notably GoodBelly’s Chief Financial Officer Maggie Mathedoittir, would expect
recommendations to be firmly backed with statistical data.

For the exclusive use of S. Colla, 2023.

This document is authorized for use only by Sebastian Colla in Applied Statistics 23 taught by Weijia Peng, Sacred Heart University from Jan 2023 to Jun 2023.

4

GoodBelly: Using Statistics to Justify the Marketing Expense  

Exhibits

Exhibit 1

Explanation of GoodBelly Sales Spreadsheet

The data came from 126 Whole Foods stores over the 10 weeks between May 4 and July 13. There was
a total of 1,386 observations.
Variable Definitions
1. Weekly Sales (Volume): The number of units sold per store per week.
2. Average Retail Price: The average retail price for GoodBelly products per store per week.
3. Sales Rep: Defined as 1 if the store had a regional sales rep (face-to-face contact) and 0 if the
store had only the national sales rep (no face-to-face contact).
4. Endcap: Defined as 1 if a store participated in an endcap promotion.
5. Demo: Defined as 1 if the store had a demo on the corresponding week.
6. Demo1-3: Defined as 1 if the store had a demo 1-3 weeks ago.
7. Demo4-5: Defined as 1 if the store had a demo at least 4-5 weeks ago.
8. Natural Retailers: The number of other natural retailers within 5 miles of each store.
9. Fitness Centers: The number of fitness centers within 5 miles of each store.
The spreadsheet has multiple tabs, some of which include the case answers. If the instructor distributes
the spreadsheet as a homework assignment, he or she should delete these tabs.

For the exclusive use of S. Colla, 2023.

This document is authorized for use only by Sebastian Colla in Applied Statistics 23 taught by Weijia Peng, Sacred Heart University from Jan 2023 to Jun 2023.

5

GoodBelly: Using Statistics to Justify the Marketing Expense  

Endnotes
1 “It’s an Inside Job.” GoodBelly.com. Accessed 18 May 2012.
2 Gray, Lynn. “Boosting Immunity Through Digestion: The Relation Among Probiotics, Prebiotics and Digestive Enzymes.” Packaged
Facts. October 2009: 1-265.
