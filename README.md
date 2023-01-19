# Ingredients-to-enhance-the-performance-of-two-stage-TCAM-based-packet-classifiers-for-IoT



Using packet classification algorithms in network equipment increases packet processing speed in Internet of Things (IoT). In the hardware implementation of these algorithms, ternary content-addressable memories (TCAMs) are often preferred to other implementations. As a common approach, TCAMs are used for the parallel search to match packet header information with the rules of the classifier. In two-stage architectures of hardware-based packet classifiers, first the decision tree is created, and then the rules are distributed among its leaves. In the second step, depending on the corresponding leaves, the second part of the rules, which includes the range of source and destination ports is stored in different blocks of TCAM. Due to inappropriate storage of port range fields, the existing architectures face the problem of wasting memory and growing power consumption. This paper proposes an efficient algorithm to encode the port range. This algorithm consists of three general steps including layering, bit allocation, and encoding. A greedy algorithm in the first step places the ranges with higher weights in higher layers. Next, an auction-based algorithm allocates several bits to each layer depending on the number of the ranges in that layer. Finally, in each layer, depending on the weight order of the ranges, the bits are given values for the intended range. The evaluation results show that unlike previous methods of storing range fields, the proposed method not only increases the speed of the classification, uses the capacity of TCAM in the second stage more efficiently.


Please cite the related paper as: 
Mahdi Abbasi, Shakoor Vakilian, Ali Fanian, Mohammad R Khosravi, Ingredients to enhance the performance of two-stage TCAM-based packet classifiers in internet of things: greedy layering, bit auctioning and range encoding,EURASIP Journal on Wireless Communications and Networking, Vol. 1, PP. 1-15, 2019.  

https://jwcn-eurasipjournals.springeropen.com/articles/10.1186/s13638-019-1617-8
