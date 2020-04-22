# JavaScript--Sum-Pairs
/*Code wars solution Sum Pairs*/


var sum_pairs=function(ints, s){
  var seen = {}
  for (var i = 0; i < ints.length; ++i) {
    if (seen[s - ints[i]]) return [s - ints[i], ints[i]];
    seen[ints[i]] = true
  }
} sum_pairs([4, 1, 2, 3, 4], );
