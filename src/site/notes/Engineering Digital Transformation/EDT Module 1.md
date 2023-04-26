---
{"dg-publish":true,"permalink":"/engineering-digital-transformation/edt-module-1/"}
---


# Manufacturing History

## Section 1: The Assembly Line

> [!NOTE]


Interchangeable parts enabled some fundamentally different approaches in manufacturing and spurred the creation of the assembly factory. The best-known early example is Henry Ford's Model T factory, where he created an efficient, continuous flow through a manufacturing line that began with raw iron ore and resulted in a final product in 81 hours (Goldratt 2006). This efficient process meant that it wasn't necessary for a journeyman to know how to do everything from end to end. Instead, very complex things were broken down into simpler components that could be maximized and quickly assembled. 

Henry Ford's assembly line created flow through the system by minimizing inventory. He accomplished this by constraining the available space on the assembly line. There just wasn't any room for storing defects to be fixed later. Additionally, problems became visible because the flow in the factory would stop. Things had to be done right the first time, and any issues interrupting the flow were very visible and needed immediate attention. This assembly line with limited space for inventory was a significant breakthrough that made automobiles affordable for the masses. It was based on a very stable, high-volume application for manufacturing.



## Section 2: Time in Motion Studies

> [!Note]

The next major innovator to come on the scene was Frederick Winslow Taylor. He was probably the first industrial engineer, and his stopwatch time study, along with Frank Gilbreth's motion studies, eventually resulted in the time and motion study approach This was the beginning of a structured approach to continuous improvement. During his studies, Taylor would watch people work, time the steps that were most efficient, and then work to ensure that all the labors were following the most efficient process. 

This resulted in some significant improvements in productivity. He faced challenges, though, because he viewed factory workers as a tool to be controlled rather than individuals who could have ideas that would help the process improve. So, while he was really effective in improving productivity, his reputation was damaged because he didn't do a very good job engaging people in the process or getting them to take ownership for the improvements they were required to implement.

## Section 3: Process Control

> [!Note]

Over time, automation and consistency in manufacturing increased. Instead of individuals handcrafting products, the process and automation were creating the products. This led to a focus on process engineering to improve quality. W. Edwards Deming is one of the fathers of this quality movement. He figured out that the best way to ensure that we're creating good high-quality products in manufacturing is to consistently monitor the process to make sure that it's always in control (Deming, 1982, chap. 11). 

This enabled a huge amount of efficiencies because when you aren't building up a lot of poor-quality product that needs to be reworked, you have a more efficient flow of product through the factory. If you build in high quality from the beginning by controlling the process, you have much higher quality and more efficient manufacturing in the end. Deming took these concepts to Japan after World War Il. While Japan was once known as a country that produced low-cost, low-quality products, implementation of these processes enabled the country to become a world leader in quality and efficiencies in manufacturing and allowed them to begin dominating the world of manufacturing.

## Section 4: Just-in-Time Inventory

> [!Note]

The approach to controlling the process enabled dramatic improvements in quality, but it wasn't enough because it is impossible to always monitor the process well enough to know that you aren't creating a quality problem and a large amount of inventory that needs to be reworked. Taïichi Ohno realized this at Toyota and created the "just-in- time inventory" approach to minimize the risk. 

This approach focuses on minimizing the amount of inventory in the system that hasn't been assembled into the final product (Poppendieck and Poppendieck 2003, chap. 1). This is important because any inventory that hasn't been assembled is at risk of rework due to the fact that quality problems may not be discovered before inventory is put into the final assembly. Henry Ford had mitigated this problem for a stable, high-volume factory building a single product by constraining space, but Ford's approach did not work as well for applications building a variety of products that couldn't use a linked assembly line.

## Section 5: Cost Accounting

> [!Note]

Factories that build a variety of things using common resources need a systematic approach for improving. The cost accounting approach of allocating all the equipment and labor cost to a product enables you to know what it costs to create the product. Using the product cost, your profit is equal to the amount you can sell the product for minus the cost to assemble it. To increase your profit, you either need to increase the selling price or reduce the manufacturing costs. 

Therefore, the focus on reducing costs is on fully utilizing your people and equipment so their costs can be allocated over more products. This cost accounting approach provides a very systematic way for improving manufacturing that has been widely adopted but is not optimal. It turns out that when you are focused on keeping everyone in the factory busy, they end up building stuff that is not required, and inventory starts stacking up, creating higher capital costs and exposure to rework.


## Section 6: Theory of Constraints

> [!Note]


Eliyahu Goldratt was the first to point out the flaws in the "keeping everyone busy" approach and took a much more system-wide view of the issue (Goldratt and Cox 2004). He argued that the number of people and equipment in the factory was really a fixed cost, and the way to systematically improve product cost was to focus on improving the flow through the entire factory instead of at each person and piece of equipment. 

Additionally, he noted that every process does not control flow through the whole factory. Instead, typically there is one bottleneck in the factory that is limiting the flow. This led to his Theory of Constraints systematic approach to improving manufacturing, which is very different and much more effective than cost accounting.

To understand the bottleneck, you need to map out the process and understand the batch size and cycle time of each step, as shown here. Once you have that, you can calculate the effective cycle time of each step. The step with the slowest effective cycle time is the bottleneck. The equation for calculating the effective cycle time in parts per hour for step 3 is:


![Pasted image 20221109122835.png|500](/img/user/assets/attachments/Pasted%20image%2020221109122835.png)


![Pasted image 20221109121940.png|500](/img/user/assets/attachments/Pasted%20image%2020221109121940.png)



## Section 7: Drum Buffer Rope

> [!Note]


Goldratt's approach to limiting inventory in the system for factories building a variety a of products was also very different from Henry Ford's practice of limiting space, because it had to be. Goldratt had factories with lots of different steps that were not connected in an assembly line, and he had to make sure excess inventory was not building up in the system. He accomplished this using his Drum Buffer Rope approach. In this approach, you find the bottleneck in the process and use its cycle time as the fastest cadence the factory can operate at without building up excess inventory. 

This is the drum that defines the rate of flow. Next, you build a small buffer of inventory in front of the bottleneck to ensure it is never starved of work. Finally, instead of just releasing work into the factory when resources are idle as is done with cost accounting, work is released into the system based on a pull from the bottleneck when it processes inventory (the rope). This approach has enabled a lot of different types of manufacturing organizations to dramatically reduce inventories and improve the flow of products.

![Pasted image 20221109123349.png|600](/img/user/assets/attachments/Pasted%20image%2020221109123349.png)

## Section 8: Kanban

>[!Note]

Taiichi Ohno needed an approach for managing the flow in Toyota's manufacturing lines because he was trying to compete with the US automobile industry, which had high-volume, dedicated factories while Toyota had low-volume factories building a variety of products. Ohno created the Kanban process for managing the flow between each of the individual manufacturing steps. In Kanban, a card or cart is used to signal when the upstream step can start building. 

Think of this as a tub or card representing a tub that holds a limited amount of finished product between each step in the manufacturing process. The upstream process can only create product when the tub or card comes back from the downstream step after the inventory has been processed. This signals to the upstream process that it can build more product without creating excess inventory. This happens between each manufacturing step so that inventory is minimized throughout, but nothing is starved by moving bottlenecks. This is very different from Drum Buffer Rope, which releases work into the front of the manufacturing process based on a pull from the bottleneck.

![Pasted image 20221109123529.png|600](/img/user/assets/attachments/Pasted%20image%2020221109123529.png)

Kanban works to ensure that there aren't short-lived bottlenecks being created somewhere else in the system as products ebb and flow through the factory. Ohno optimized the system to a level above Drum Buffer Rope to achieve the efficiencies of Henry Ford's high-volume, stable manufacturing in a low- volume factory with lots of variability.


## Section 9: Toyota Kata

> [!Note]

Kanban helped control inventory levels and improve flow, but Ohno was going to need even more if Toyota was going a to be a competitor in the world market. They needed to improve every aspect of their operations faster than anyone else, So Ohno created the Kata process, a systematic approach to continuous improvement that engages the entire organization (Rother, 2010). It is based on the scientific method of defining the problem, proposing a hypothesis for improvement, implementing the change, monitoring the result of the change to see if it had the desired effect. This approach works very well in manufacturing when the goal is to improve the process used to create the same product over and over again.

With the Kata process, Taiichi Ohno made sure he was able to engage everyone in the continuous improvement process all the way down to the factory worker. The manager's role was to help train everyone in the process and ensure they were using the scientific method. There were very specific steps that everyone was expected to follow that included documenting the plans with what they call the A3 report template because everything can be summarized on an A3 size sheet of paper, as shown here (Sobeck and Smalley 2008, 33).

![Pasted image 20221109133700.png|500](/img/user/assets/attachments/Pasted%20image%2020221109133700.png)


The Toyota production system and the Kata approach got everyone focused on continuous improvement. It was everyone's job to identify problems and engage in getting them fixed. On their production lines, they installed Andon Cords that enabled anyone who saw a problem to pull the cord and stop the line so they could fix the process. This was important because if there was a process problem, they wanted it fixed immediately before the process started creating additional defective products that would have to be reworked.


## Section 10: Theory of Constraints

> [!Note]
> 

Goldratt was a real champion of Lean Six Sigma and the impact it could have on improving processes. He took it one step further by showing that improvements not focused on the constraint or bottleneck in the process will not improve the flow of the overall system. His Theory of Constraints approach was the answer to this problem (Goldratt and Cox 2004, 360). 

It ensures that the improvements are focused on addressing the bottleneck by using five focusing steps: 
1. Identify the system constraint. 
2. Decide how to exploit the system constraint. 
3. Subordinate everything else to above decisions. 
4. Elevate the constraint. 
5. If in the previous steps a constraint has been broken, go back to step one but do not allow the inertia to cause a system constraint.

This is a very systematic approach for continuous improvement that focuses on improving the flow of value through an organization that can be applied broadly beyond manufacturing. A great example of this is presented in the book The Goal, which is the model Gene Kim et al., used for writing the IT example in their book The Phoenix Project.



## Section 11: Embracing New Capabilities

> [!Note]

In Beyond the Goal: Theory of Constraints, Goldratt demonstrated how to deal with fundamentally new capabilities. When you introduce new capabilities, you need to evaluate the rules that were based on the previous capabilities and be willing to change those rules to exploit the new capabilities (Goldratt 2005, chap. 1). He used the example of rolling out software for material requirements planning (MRP) to highlight the approach. MRP tries to figure out how much material to order and how much of everything to manufacture based on orders and inventories. Before software, calculating how much to order and how much to build for the next month was a very labor-intensive process. Organizations would run this process once a month. Factories of 300 people would traditionally have around 20 people just to run these calculations. When software came along, this was one of its first applications because these are the types of calculations computers and software can do very well. The computer could easily run all the MRP calculations overnight.

Black & Decker was one of the first companies to rollout MRP systems. They saw dramatic improvements in their ability to commit to new orders while running with historically low levels of inventory. Their responsiveness to their customers increased and cost decreased as a result. The interesting thing was as MRP rolled out to more and more organizations, those organizations weren't seeing the same results.

They were spending millions of dollars rolling out these MRP systems, and the lack of results was frustrating. Goldratt examined the rollouts and the discoveries the organizations made. What he found was that there was a fundamental rule from the old system that had not changed. People had simply incorporated the old rule into the new capability. They had not changed how often they ran MRP even though it was now less labor intensive. They were still only running it once a month. This is very different from Black & Decker's practice of efficiently running this process on an ongoing basis. They were planning and running MRP several times a week and optimizing what they built based on current orders and inventory levels. They were much more responsive to their customers and had less inventory than the rest of the industry because once they changed their capabilities, they changed the rules to take advantage of those new capabilities. Where other organizations just saw productivity improvements for their planning process they ran once a month, Black & Decker by changing the rules fundamentally changed the responsiveness of their entire organization by using this capability more frequently.


# Conclusion

Manufacturing has a long history of creating systematic approaches to improving how it develops and manufactures products which has had a significant impact on overall quality and productivity. Using a suboptimal approach like cost accounting was proven to be detrimental to the effectiveness of organizations. The implication for software is that it should be able to achieve similar benefits from systematic approaches as long as we pick the right ones and the industry stays focused on continually improving them. There is a lot that software can learn from the manufacturing processes that have proven over the years to be effective, but those approaches can't simply be copied wholesale. Software is different. The systematic approaches that will work best for software need to be modified to address its unique capabilities and characteristics.

Now that you have an understanding of manufacturing's history for creating systemic approaches to improvement, please complete the following Assessment. Then we will begin our journey on developing a systematic approach for continually improving on how we can develop and deliver software.


## Quiz

### Q1
Given this four-step manufacturing process, how many part per hours can step 4 create? 

15 parts per hour? 
10 parts per hour?
5 parts per hour?
12 parts per hour?


![Pasted image 20221109134248.png|500](/img/user/assets/attachments/Pasted%20image%2020221109134248.png)

### Q2



![Pasted image 20221109135949.png|500](/img/user/assets/attachments/Pasted%20image%2020221109135949.png)