# Experiment 4

## Implementation of Register using Flip-Flops in Logisim

---

## Objective

The objective of this experiment is to design and implement a register using D flip-flops in Logisim Evolution. The aim is to understand data storage, sequential circuits, and the role of clock signals in digital systems.

---

## Background Study

A register is a group of flip-flops used to store binary data. Each flip-flop stores one bit, and multiple flip-flops together form a register capable of storing multi-bit data.

D (Data) flip-flops are commonly used in registers because they store the value present at the input when a clock pulse is applied.

Registers operate based on clock signals. On every clock pulse, the input data is transferred and stored in the flip-flops.

Registers are widely used in digital systems for temporary data storage, data transfer, and synchronization.

---

## Experiment Description

In this experiment, an 8-bit register was implemented using multiple D flip-flops connected in parallel.

Each flip-flop represents one bit of the register. All flip-flops share a common clock signal to ensure synchronized operation.

The input data lines were connected to the D inputs of the flip-flops. When the clock signal is triggered, the input values are stored simultaneously across all flip-flops.

Logic gates were used to control and manage the input signals before storing them in the register. The stored output was observed using output indicators.

---

## Circuit Diagram

(Uploaded along with the file)

---

## Observations

1. The register successfully stored the input data on the application of the clock signal.  
2. All flip-flops updated their values simultaneously, showing proper synchronization.  
3. The output remained stable until the next clock pulse was applied.  
4. The stored binary values matched the given input values.  
5. The circuit behaved correctly for different input combinations.  

---

## Result

The 8-bit register was successfully implemented using D flip-flops in Logisim. The circuit correctly stored and displayed input data based on clock pulses.

---

## Conclusion

This experiment helped in understanding the working of registers and sequential circuits. It demonstrated how multiple flip-flops can be combined to store multi-bit data and highlighted the importance of clock signals in controlling data flow and synchronization in digital systems.
