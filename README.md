
<div align="center"><img src="https://history-computer.com/ModernComputer/Relays/images/stibitz_portrait2.jpg" alt="Konrad Zuse, the creator of the first relay computer" width="250" height="380" /></div>
<h3>Relay computers of George Stibitz</h3>
<p>The <em>Bell Telephone Laboratories</em> was incorporated in 1925 as the basic research facility for the Bell System. Thus began an institution that has become synonymous with fundamental and exciting research at the frontiers of physics, chemistry and other branches of modern science. In this exciting place during the next several decades will be made a lot of researches, which will bring to several inventors a Nobel prize. A lot of inventions in the field of computers will be made also here, let's mention only the first logical schemes with diodes (1942), point transistor (1947), first fully transistor computer (TRADIC, 1955), first modem (1960), first single-chip 32-bit processor (1980), operating system UNIX (1969), programming language C (1973) and C++ (1983), etc.</p>

<p><img src="https://history-computer.com/ModernComputer/Relays/images/ModelKStibitz.jpg" alt="Stibitz's K-Model" width="300" height="268" hspace="5" vspace="0" border="0" align="left"  />In a late evening of November, 1937, a research mathematician at the Bell Labs, George Stibitz (<a href="../../People/StibitzBio.html">biography of George Stibitz</a>), left his working place to go home, taking from the Bell stockroom two telephone relays, a couple of flashlight bulbs and, a wire and a dry cell. At home he sat behind the kitchen table and started to assemble a simple logical device, which consisted from the above-mentioned parts and a switch, made from a tobacco tin. He soon had a device, which proved to be the first relays binary adder, in which a lighted bulb represented the binary digit "1" and an unlighted bulb, the binary digit "0." 
His wife Dorothea named it the <em>K-model</em>, after "kitchen table". The next day Stibitz's took the <em>K-model</em> to the Labs to show the colleagues, and they speculated on the possibility of building a full-size calculator out of relays. His colleagues reasoned that any practical relay computer, using binary arithmetic, would need perhaps hundreds of relays, thus making it both bulkier and more expensive than the commercial mechanical calculators then in use at the Labs.</p>



<p>But what George Stibitz realized was, that a relay calculator could perform not just one but a sequence of calculations, with relay circuits directing the order and storing interim results as needed. Specifically,
it could perform the sequence of operations required to perform multiplication and division of complex numbers: two mathematical operations that researchers elsewhere at the Bell Labs frequently performed in connection with filter and amplifier design for long-distance circuits. At Labs in the 1930s, a roomful of human "computers" figured complex number quotients and products using commercial mechanical calculators. The calculations themselves are straightforward enough: a complex multiplication requires about six simple arithmetic operations, while complex division requires about a dozen operations, and each requires temporary storage of a few intermediate results.</p>
<p>Stibitz did not know that in Berlin <a href="Zuse.html">Konrad Zuse</a> was doing almost the exact same thing at the same time. Stibitz however did know that Claude Shannon also had studied the correspondence of statements of symbolic logic with binary relay circuits while a graduate student at MIT. Shannon wrote his graduate thesis (published in 1938) on that subject, and then went to Bell Labs, where he and Stibitz learned of each other's work. But Shannon was not actively involved in the design of the computers of Stibitz. Clearly the idea of using relays to implement binary logic was common in the late 1930's. (a similar discovery was made in Japan).</p>

<div align="center"><img src="https://history-computer.com/ModernComputer/Relays/images/StibitzTerminalSchema.jpg" alt="Drawing of the teletype of the Complex Number Computer" width="400" height="246" /></div>
<p class="picture_notes">Drawing of the teletype of the Complex Number Computer</p>

<p>When Stibitz first demonstrated his K-model computer for company executives, they were not very impressed. <cite>There were no fireworks, no champagne</cite>, as he remembered later on. Less than a year later, however, Bell executives had changed their minds about the Stibitz invention. An important factor in that decision was the increasing pressure on Bell to find a way of solving its increasingly complex mathematical problems. The company agreed to finance construction of a large experimental model of Stibitz's invention. Stibitz completed the designs in February, 1938, and the construction of the machine began in April, 1939, by Samuel Williams, a switching engineer in Bell. The final product was ready in October and was first put into operation on January 8, 1940, and remained in service until 1949. As Bell Labs built other relay computers during the war, its name was changed from the initial <em>Complex Number Computer</em> to <em>Model 1</em>. The cost was some 20000 USD. <br />
Initially the <em>Complex Number Computer</em> performed only complex multiplication and division, but later a simple modification enabled it to add and subtract as well. It used about 400-450 binary relays, 6-8 panels, and ten multiposition, multipole relays called "crossbars" for temporary storage of numbers. The machine used the decimal system with the decimal point fixed at the beginning of each number. Internally, four binary relays coded each digit, using a code that represented a decimal digit n by the binary code for n+3; this simplified the problem of digit carry and subtraction (excess-three binary coded decimal is still called "Stibitz-code" today). The machine handled ten-digit numbers in its registers, but displayed and printed eight-digit answers (range ??0.99999999). It used "prefix" notation: that is, operators keyed the arithmetic operations before they keyed in the operands. For example, to multiply the two complex numbers (2+3i) by (4+5i), the operator would key in (see the upper drawing of the keyboard):<br />
&nbsp;&nbsp;&nbsp;<strong>M +.2 +i .3 +.4 -i .5 =</strong><br />



The letter <em>M</em> stands for multiply (the letter <em>D</em> in the keyboard is for division). Note the location of the decimal point before each of the four numbers. The machine would actually be calculating (0.3+0.5i) x (0.4-0.2i), and print the answer <em>0.07000000+i 0.22000000</em>. The operator would have to scale the results accordingly (multiply by 100). A simple adding operation took about 100 mS, while multiplication of 2 complex numbers took about forty-five seconds.</p>

<p><img src="https://history-computer.com/ModernComputer/Relays/images/StibitzTerminal.jpg" alt="Stibitz's Terminal" width="200" height="226" hspace="5" vspace="0" border="0" align="left"  />The calculating unit has 4 registers and is completely separated from the input/output unit, which is a special terminal (see the nearby photo). The computer itself was kept in an out-of-the-way room in the labs, where few ever saw it. The operators accessed it remotely using one of three modified teletype machines (keyboard and a printing device), connected to processor by a multiple-wire buss and placed elsewhere, which however cannot work simultaneously. </p>

<p>Stibitz developed further the idea of remote, multiple access to a computer. On September 11, 1940 the <em>American Mathematical Society</em> met at Dartmouth College in Hanover, New Hampshire, a few hundred miles north of the building of Bell Labs in New York, where was the Complex Number Computer. Stibitz arranged to have the computer connected by telephone lines (28-wire teletype cable) to a teletype unit installed there. The Complex Number Computer worked well, and there is no doubt it impressed those who used it. The meeting was attended by many of America's most prominent mathematicians, as well as individuals who later led important computing projects (e.g., John von Neumann, John Mauchly, Norbert Wiener and Garrett Birkhoff). The Dartmouth demonstration foreshadowed the modern era of remote computing, but remote access of this type was not repeated for another ten years.</p>

<p><img src="https://history-computer.com/ModernComputer/Relays/images/CNCofStibitz.jpg" alt="CNC computer of Stibitz, copyright Lucent Technologies" width="289" height="390" hspace="3" align="left" />The Complex Number Computer was not programmable. A combination of relay circuits permanently controlled its sequence of operations. Those relays were of the same type as the ones used to handle the numbers, but the machine did not have a separate, clearly defined part that handled the "control" of the computing sequence. (Later Bell Labs computers did.) The concept of programmability arose at Bell Labs only after the Complex Number Computer was built, after its builders saw that its basic computing elements were unduly restricted by its marriage to control circuits tying it to nothing but complex arithmetic. (Besides complex arithmetic, they tried to get the machine to perform polynomial arithmetic, of which complex arithmetic is a special case. But the machine was too restricted for that.)</p> 

<p>The success of Complex Number Computer encouraged Stibitz to propose more ambitious designs that included an ability to modify the calculator's operations by perforated tape. At first the Labs turned down his proposals, but with the entry of the United States into the Second World War in December 1941, Bell Labs shifted
its priorities toward military projects that involved more computation than its peacetime research. Most of their wartime accomplishments were in the design of analog computers. But they also built five digital relay computers for military purposes, and one more after the war's end for their own use, making a total of seven digital machines counting the Complex Number Computer.</p>



<p>The first of these calculators for military use was the <em>Relay Interpolator</em>, installed in Washington, D.C. in 1943 and later known as the <em>Model II</em>. It was built from 440 relays and memory capacity of 7 numbers. Speed of multiplication was 4 seconds (multiplication by repeated addition). It mainly solved problems related to directing antiaircraft fire, which it did by executing a sequence of arithmetic operations that interpolated function values supplied to the machine by paper tapes. Like the Complex Number Computer, it was a special-purpose machine; however, its arithmetic sequence was not Relay Calculators permanently wired but rather supplied by a "formula tape" (five-channel paper tape) cemented into a loop. Different tapes therefore allowed one to employ different methods of interpolation. The Model II could not do much besides interpolation, but as interpolation is a process that lends itself to the solution of many problems in science and engineering the machine was kept busy by other government agencies long after the war ended.</p>

<p>The next two machines, designed by Stibitz are the <em>Ballistic Computer</em> and the <em>Error Detector Mark 22</em> (later known as Models III and IV), were identical machines, the first installed in 1944 at Fort Bliss, Texas, and the second in early 1945 in Washington (each one cost 65000 USD). They contained some 1400 relays and had memory capacity of 10 numbers. Speed of multiplication was 1 second (multiplication by table look-up). These machines also used paper tapes for data and formula input, with the arithmetic sequence supplied by a loop of paper tape. The Models III and IV, like the Model II, also solved problems relating to the aiming and tracking of antiaircraft guns. They were, however, more sophisticated machines, having the ability not only to perform interpolation but also to evaluate the ballistic equations describing the path of the target airplane and of the antiaircraft shell. An additional paper tape directed which of those functions the machine was to evaluate. Thus, the Models III and N were the first of the Bell Labs digital calculators to have some degree of general programmability, although neither was a fully general-purpose calculator. Their memory and arithmetic units had modest capabilities: only six decimal digits of precision, a memory of ten numbers for each machine.</p>

<p>The largest computer in the series and the last, designed by Stibitz, was the Model V, of which Bell Labs built two copies for the military in 1946 and 1947. It was a huge (weight 10 tons) and very expensive (500000 USD) machine. Each contained over nine thousand relays and handled numbers expressed in scientific notation. The store could hold up to thirty numbers, and paper tape readers fed in both program steps and numerical data. Speed of multiplication 0.8 sec. The most interesting aspect of the Model V's design was that it had two separate arithmetic units, each capable of operating as an independent computer with its own memory registers and input-output devices. Small-scale problems could be run in pairs on the machine, saving time, while bigger problems could take over both processors. Associated with each processor (using the modern term) were fifteen memory registers, for a total of thirty for the whole machine. A master control unit directed instructions to one or both processors according to their availability. This control unit was separate from the control units in the processor that directed the sequence of arithmetic, memory, and input/output operations; it controlled the control, so to speak. (Stibitz called it a "superbranching" capability.) Thus in a very real sense the Model V had what is now called an "operating system"-a control unit that supervises and manages the flow of work through a computer.</p>

<p>Besides programming power, the later Bell computers stressed extraordinary reliability. Relays, used as a basic element for logical and memory operations, have a tendency to fail intermittently. Should a piece of dust lodge itself between two relay contacts, that circuit will fail, though the rest of the relay will be fine. After a few cycles, the dust particle may shake itself loose, after which everything will return to normal. Thus an entire computation may be way off without any machine failure showing up during a diagnostic session.</p>

<p>Bell's engineers designed computer circuits that checked themselves at every step of a computation. The circuits were designed not only to add, subtract, store numbers, and so on; they were also designed to check that they had done those things correctly, and to stop the machine otherwise. Bell's engineers were also guided by their experience in designing telephone circuits that had to operate long hours unattended in often hostile environments. Those circuits were designed to be repaired by semi-skilled technicians; telephone service would be terribly costly if an engineer had to be called in every time a phone line went down or a customer's phone went dead. The Bell Labs Models II through VI used a system whereby not four but seven binary relays coded each decimal digit. They were divided into two groups of two and five relays; the decimal code was as follows:



<table width="300" border="1" cellspacing="0" cellpadding="3">
  <tr>
    <td width="100"><div align="center">Decimal digit</div></td>
    <td colspan="2"><div align="center">Relays</div></td>
    </tr>
  <tr>
    <td width="100">0</td>
    <td width="150">01</td>
    <td width="200">00001</td>
  </tr>
  <tr>
    <td width="100">1</td>
    <td width="150">01</td>
    <td width="200">00010</td>
  </tr>
  <tr>
    <td width="100">2</td>
    <td width="150">01</td>
    <td width="200">00100</td>
  </tr>
  <tr>
    <td width="100">3</td>
    <td width="150">01</td>
    <td width="200">01000</td>
  </tr>
  <tr>
    <td width="100">4</td>
    <td width="150">01</td>
    <td width="200">10000</td>
  </tr>
  <tr>
    <td width="100">5</td>
    <td width="150">10</td>
    <td width="200">00001</td>
  </tr>
  <tr>
    <td width="100">6</td>
    <td width="150">10</td>
    <td width="200">00010</td>
  </tr>
  <tr>
    <td width="100">7</td>
    <td width="150">10</td>
    <td width="200">00100</td>
  </tr>
  <tr>
    <td width="100">8</td>
    <td width="150">10</td>
    <td width="200">01000</td>
  </tr>
  <tr>
    <td width="100">9</td>
    <td width="150">10</td>
    <td width="200">10000</td>
  </tr>
</table>
<p>Bell Labs called this system a "bi-quinary" notation, since the relays had a weight of either one or five. Actually, it is not a combination of those number bases; rather, it is a seven-bit, mixed decimal code. All the Bell Labs relay computers worked in decimal arithmetic. A special circuit checked to see that two and only two relays were energized for each decimal digit. Another circuit checked that for each group one and only one relay was on&#8212;that prevented two separate errors from canceling each other out, although certain unusual combinations of malfunctions could go undetected.</p> 
