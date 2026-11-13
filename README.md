challenge :::

Select and layout a synchronous DC-DC buck converter. 
Input: 12 V; 
Output: 5 V
and up to 3 A

here, i track it.

some problems i noticed with my design:
- [ ] as the datasheet's layout example seems to target 2+ layer boards, i just opted for regular traces with the vias instead of the SW copper pour in the internal layer. cant really know if it causes issues. should not in theory
- [ ] having issues with 3D models loading
- [ ] GND and VIN copper zones are quite close to each other. Does it cause noise issues? Should not, huh, as GND is not a signal traces?
- [ ] Traces and via parameters should be good for high current spikes. Wanna see how it performs on the physical bring-up.
- [x] ...
