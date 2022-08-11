# Variations on Noetherianness
This repository contains the Agda code associated with the paper "D. Firsov, T. Uustalu, N. Veltri. [Variations on Noetherianness](http://dx.doi.org/10.4204/eptcs.207.4)" published at MSFP 2016.

## Contents

- Definitions of notions of finiteness 
	- Listable.agda
	- Noetherian.agda
	- Streamless.agda
	- Bounded.agda
	- AlmostFull.agda
- NoethExamples.agda - examples of noetherian sets
- Properties of notions of Noetherianness 
	- NoethAccDecEq.agda 
		-- NoethDecEq
	- NoethRels.agda 
		-- NoethAcc→NoethAccS
		-- NoethAccS→NoethSet
		-- NoethSet→NoethAccS
		-- NoethAccS→NoethGame
		-- NoethExposeX→Listable
	-  StreamlessProps.agda
		-- NoethAccS→StreamlessS
		-- NoethAcc→Streamless
	- AlmostFullProps.agda 
		-- AFEq→NoethAcc
		-- NoethAcc→AFEq
- Separating notions
	- NotNotIn.agda -- separating NoethAcc from NoethAccS
	- MaybeProp.agda -- separating NoethExpose from Bounded
	- PropSet.agda -- separating Listability from NoethExpose

## Setup
Agda @ 2.6.0.1, agda-stdlib @ 1.1-1
