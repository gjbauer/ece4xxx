# **Course Syllabus: Advanced Digital Design with SystemVerilog**

## **Course Information**
- **Course Title**: Advanced Digital Design with SystemVerilog
- **Course Code**: ECE 4xxx/5xxx
- **Credit Hours**: 3
- **Prerequisites**: Computer Hardware (CS 2220 or equivalent), Introduction to Programming
- **Level**: **Dual-listed Undergraduate/Graduate** (4000-level UG / 5000-level Grad)
  - *Rationale*: Core content suits advanced undergraduates, while graduate students complete additional advanced modules and research components

---

## **Course Description**
This course covers advanced digital design methodologies using SystemVerilog, integrating both design and verification techniques. Students progress from basic RTL design through complex system integration, with emphasis on verification-driven design methodologies including UVM basics. The course emphasizes hands-on implementation with industry-relevant tools and practices.

---

## **Learning Objectives**
Upon completion, students will be able to:
1. Design complex digital systems using SystemVerilog RTL
2. Implement verification environments using SystemVerilog testbenches
3. Apply industry-standard verification methodologies (UVM basics)
4. Integrate multiple IP blocks into functional systems
5. Debug digital designs using simulation tools and waveforms
6. Write synthesizable code adhering to industry best practices
7. Create coverage-driven verification plans

---

## **Textbook & Resources**
- **Primary**: "SystemVerilog for Design" by Sutherland, Davidmann, and Flake
- **Secondary**: "SystemVerilog for Verification" by Chris Spear
- **Reference**: "UVM Primer" by Ray Salemi
- **Tools**: ModelSim/QuestaSim (academic license)
  - Open Source Alternatives: Icarus Verilog (supports a subset of SystemVerilog), GTKWave
  - Optional: Synopsys VCS

---

## **16-Week Course Schedule**

### **Module 1: Fundamentals (Weeks 1-4)**
**Week 1: Course Introduction & SystemVerilog Basics**
- Lecture: Design methodology, Verilog vs SystemVerilog
- Lab: Tool setup, "Hello World" simulation
- Assignment: Combinational ALU (from Week 1 plan)

**Week 2: Sequential Design & Timing**
- Lecture: Clocks, resets, metastability, timing constraints
- Lab: Flip-flop variants and timing analysis
- Assignment: Parameterizable shift register

**Week 3: Finite State Machines**
- Lecture: State machine styles, encoding, optimization
- Lab: FSM design and debugging techniques
- Assignment: Sequence detector with testbench

**Week 4: Memory Systems & Testbench Basics**
- Lecture: Memory architectures, verification fundamentals
- Lab: FIFO operation and testbench structure
- Assignment: Synchronous FIFO with basic verification

### **Module 2: Verification Techniques (Weeks 5-8)**
**Week 5: Advanced Testbenches**
- Lecture: Constrained random verification, scoreboarding
- Lab: Random stimulus generation
- Assignment: Enhanced FIFO testbench with coverage

**Week 6: Interfaces & Protocols**
- Lecture: Interface constructs, UART/SPI basics
- Lab: Protocol analysis and implementation
- Assignment: UART transmitter with interface

**Week 7: Object-Oriented Verification**
- Lecture: OOP concepts in SystemVerilog
- Lab: Class-based testbench development
- Assignment: AXI-Lite transaction class and environment
- **Grad Requirement**: Additional inheritance hierarchy

**Week 8: Design for Test & Midterm**
- Lecture: DFT principles, scan chains, ATPG
- Lab: Scan insertion and test pattern generation
- **Midterm Exam**: Covers Weeks 1-7
- Assignment: Scan-enabled design

### **Module 3: Advanced Topics (Weeks 9-12)**
**Week 9: Standard Bus Protocols**
- Lecture: AMBA AXI protocol family
- Lab: Protocol timing analysis
- Assignment: AXI-Lite slave interface
- **Grad Requirement**: Implement full AXI4 subset

**Week 10: UVM Fundamentals**
- Lecture: UVM architecture, components, phases
- Lab: UVM testbench setup and execution
- Assignment: Minimal UVM environment

**Week 11: Arbitration & Resource Management**
- Lecture: Arbitration algorithms, fairness metrics
- Lab: Performance analysis of arbiters
- Assignment: Round-robin arbiter with verification
- **Grad Requirement**: Compare multiple arbitration schemes

**Week 12: Error Correction & Robust Design**
- Lecture: ECC, fault tolerance, reliability metrics
- Lab: Error injection and analysis
- Assignment: Hamming code encoder/decoder

### **Module 4: System Integration & Verification (Weeks 13-16)**
**Week 13: Formal Verification & Assertions**
- Lecture: SVA, property specification, formal methods
- Lab: Assertion writing and debugging
- Assignment: Assertion-based verification for AXI interface

**Week 14: System Integration**
- Lecture: System-level design, IP integration, verification planning
- Lab: Top-level integration and debugging
- Assignment: Integrated system design
- **Grad Requirement**: Add performance monitoring features

**Week 15: Final Project Development**
- Lecture: Design review methodologies, documentation standards
- Lab: Project work sessions with instructor feedback
- Assignment: RISC-V core development (milestone 1)

**Week 16: Final Presentations & Review**
- Student presentations of final projects
- Course review and industry outlook
- **Final Exam Period**: Project submission and demonstration

---

## **Grading Structure**

### **Undergraduate (ECE 4xxx)**
- Assignments (14): 40%
- Midterm Exam: 20%
- Final Project: 25%
- Quizzes/Participation: 15%

### **Graduate (ECE 5xxx)**
- Assignments (14): 30%
- Midterm Exam: 15%
- Final Project: 30%
- Research Paper/Extended Project: 15%
- Quizzes/Participation: 10%

**Graduate Differentiation**:
1. Additional requirements in assignments (marked above)
2. Research paper on advanced verification methodology
3. Extended final project with written report (conference paper format)
4. Lead discussion sessions on advanced topics

---

## **Laboratory Facilities**
- **Software**: Licensed EDA tools (ModelSim/QuestaSim, optional Synopsys/Cadence tools)
- **Hardware**: Optional FPGA boards for final project implementation
- **Computing**: Linux workstations with sufficient processing power for simulations

---

## **Course Policies**
1. **Collaboration**: Design discussions encouraged, but code must be individual work
2. **Late Policy**: 10% deduction per day, up to 3 days late
3. **Academic Integrity**: All work must be original; proper citation required
4. **Accommodations**: ADA accommodations coordinated through university services

---

## **Learning Outcomes Assessment**
- **ABET Alignment** (for Engineering programs):
  - Ability to design digital systems meeting specifications (Assignments 1-14)
  - Ability to communicate technical content (Final presentation)
  - Understanding professional and ethical responsibility (Collaboration policies)
  - Recognition of need for lifelong learning (Industry methodology coverage)

---

## **Recommended Preparation for Students**
1. Review basic digital logic (combinational/sequential circuits)
2. Install required software before Week 1
3. Basic familiarity with any programming language (C/C++/Python/Java)
4. For graduate students: preliminary reading on verification methodologies

---

## **Why Dual-Listed?**
This course bridges undergraduate fundamentals with graduate-level depth:
- **Undergraduates** gain industry-ready skills for entry-level FPGA/ASIC design roles
- **Graduate students** develop research capabilities in verification methodologies
- The verification focus makes it relevant for both design and verification career paths
- Growing industry demand justifies offering at both levels

The course could be positioned as a **capstone design course** for undergraduates or a **core specialization course** for graduate students in computer engineering or VLSI tracks.
