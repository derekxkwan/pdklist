# pdklist
gpl v 3 pd vanilla list abstractions

## GENERAL
- pdkl-cup - count up or down in [lower,upper)
- pdkl-ddrip - drip atoms on demand in chunks
- pdkl-ddrip2 - looping element dripper
- pdkl-defaults - populate outgoing list with defaults
- pdkl-dinterl2 - deinterlace into 2 lists
- pdkl-dirjoin - take list of directories and join into path
- pdkl-dot - dot product of two lists
- pdkl-drip - output elements of varying size 1-by-1 
- pdkl-eltcmp - element comparator
- pdkl-eltsub - substitute matching elements of a list
- pdkl-everynth - get every nth elt of a list
- pdkl-faro - faro shuffle
- pdkl-fill - accumulate entries of a list
- pdkl-filln - accumulate entries into n-elt list
- pdkl-find - find first elt matching comparator (else bang)s
- pdkl-fyshuf - fisher-yates shuffle
- pdkl-insert - insert provided elts into given list at given idx
- pdkl-intersp - put thing in between every element of a list
- pdkl-interl2 - interlace 2 lists
- pdkl-interl3 - interlace 3 lists
- pdkl-interl4 - interlace 4 lists
- pdkl-last - get last n elts
- pdkl-map - list mapper
- pdkl-map2 - map using a second list as arguments
- pdkl-memq - return sublist starting at comparator
- pdkl-pathjoin - join parts of phath into full path
- pdkl-pathparts - spilt full path into individual components
- pdkl-pathsplit - split path into constituent parts
- pdkl-prepend - list prepend with trim
- pdkl-randi - list of random ints
- pdkl-randi2 - list of random ints within list of ranges
- pdkl-reduce - list reducer
- pdkl-reduce2 - list reducer (but keeps track of steps)
- pdkl-ref - get nth entry of a list
- pdkl-rev - list reversal
- pdkl-rfill - accumulate entries of a list in reverse
- pdkl-rgate - random gate with weight list (needs iemguts for now)
- pdkl-rmap - reversed list mapper
- pdkl-rot - rotate list by x elts
- pdkl-rpatt1 - random pattern generator
- pdkl-rpt - repeat x elts starting with y z times
- pdkl-rpt2 - a more sophistsicated repeater
- pdkl-rrand - list of random floats
- pdkl-rrand2 - list of random floats within list of ranges
- pdkl-set! - replace nth elt with list with variable sized elements
- pdkl-setf! - replace nth entry of a list with float
- pdkl-seq1 - list sequencer
- pdkl-seqct1 - sequenced counter (helpful for indexing!)
- pdkl-sieve - only let x-chunk elements through as defined by a list
- pdkl-sieve2 - only let x-chunk elts through as defined by a list but (replace other elts with a float)
- pdkl-split2 - split a list into 2
- pdkl-split3 - split a list into 3
- pdkl-stut1 - stutter elts of a list x times in y chunks
- pdkl-swap - swap variable sized elements at two indices
- pdkl-swapf - swap floats at two indices
- pdkl-symcmp - symbol comparator
- pdkl-symjoin - join list of symbols together with a symbol
- pdkl-symsplit - split incoming symbol into components by given char
- pdkl-wrand - weighted random (needs iemguts for now for canvasargs)
- pdkl-xrndelt- non-repeating random element from a list


## GENERATORS
- pdkl-arith - arithmetic series generator
- pdkl-geom - geometric series generator
- pdkl-numpatt - generate patterns from number lists
