

* Regex that matches either goat or moat, but not boat.
- /\b[gm]oat\b/gm;

* Single regex that matches either of these:

    antelope rocks out
    antelopes rock out
- /\b(antelope)s? (rock)s? out\b/g;

* Regex that matches dates in YYYY-MM-DD format.
- /\b(\d{1,4})\-(\d{1,2})\-(\d{1,2})*\s/gm;

* Come up with regexes for the two above sequences. The one to set the
    cursor position should accept any digits for the row and column. The
    bold sequence need only accept `1` (and is a trivial regex). (ESC is
    a single character which can be represented with `\e` in the regex.)
- /(\e\[(\d+\;\d+f)) | (\e\[(\dm))/g

# Algorithms & Theory 

## Exercise One

   a) O(n)
   b) O(log n)
   c) O(log n)
   d) O(n log n)
   e) O(n!)
   f) O(n)
   g) O(n)

## Exercise Two - rang out of time
int main() {
double top = 0.0;
double min = a[0];
for (int i = 0; i < N; i++) {
    min = Math.min(a[i], min);
    best = Math.max(a[i] - min, top);
  } 
  printf()
}
b) To determine the value of f, you will have to drop an egg from the first floor. Then proceed through the floors in sequential order, dropping an egg on each floor until a break. 