# IncrementingLLFSM
Examples of the Kripke Structures generation for the Microwave and Incrementing LLFSM.

This repository contains the results for the paper "Versatile but Precise Semantics for Logic-Labelled Finite State Machines".  The Kripke Structures are stored in the following folders:


<dl>
    <dt><strong>incrementing:</strong></dt>
    <dd>
        <p>Contains Kripke Structures for different execution semantics for the Incrementing LLFSM:</p>
        <dl>
              <dt><strong>single:</strong></dt>
              <dd>Contains Kripke Structures for executing a single instance of the Incrementing LLFSM.</dd>
              <dt><strong>multiple-round-robin:</strong></dt>
              <dd>Contains Kripke Structures for executing two Incrementing LLFSMs in round-robin, taking snapshots per ringlet execution. </dd>
              <dt><strong>multiple-single-snapshot:</strong></dt>
              <dd>Contains Kripke Structures for executing two Incrementing LLFSMs taking a snapshot per schedule cycle, as opposed to per ringlet.</dd>
        </dl>
    </dd>
    <dt><strong>microwave:</strong></dt>
    <dd>
        <p>Contains Kripke Structures for different execution semantics for the microwave:</p>
        <dl>
            <dt><strong>round-robin:</strong></dt>
            <dd>Contains Kripke Structures for executing the microwave in round-robin, taking snapshots per ringlet execution.</dd>
            <dt><strong>single-snapshot:</strong></dt>
            <dd>Contains Kripke Structures for executing the microwave taking a snapshot per schedule cycle, as opposed to per ringlet.</dd>
        </dl>
    </dd>
</dl>

Each folder contains a .gv file which is a graphviz file in the dot format, and a .smv file which can be used by NuSMV.
