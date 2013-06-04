# algo-toolbox

## DESCRIPTION:

Written by [Mohamed Amine LABIDI](http://about.me/medaminelabidi)

## COMPLETED:

    * Heaps              Containers::Heap, Containers::MaxHeap, Containers::MinHeap
    * Priority Queue     Containers::PriorityQueue
    * Deque              Containers::Deque, Containers::CDeque (C ext)
    * Stack              Containers::Stack
    * Queue              Containers::Queue
    * Red-Black Trees    Containers::RBTreeMap, Containers::CRBTreeMap (C ext)
    * Splay Trees        Containers::SplayTreeMap, Containers::CSplayTreeMap (C ext)
    * Tries              Containers::Trie
    * Suffix Array       Containers::SuffixArray

    * Search algorithms
      - Binary Search            Algorithms::Search.binary_search
      - Knuth-Morris-Pratt       Algorithms::Search.kmp_search
    * Sorting algorithms           
      - Bubble sort              Algorithms::Sort.bubble_sort
      - Comb sort                Algorithms::Sort.comb_sort
      - Selection sort           Algorithms::Sort.selection_sort
      - Heapsort                 Algorithms::Sort.heapsort
      - Insertion sort           Algorithms::Sort.insertion_sort
      - Shell sort               Algorithms::Sort.shell_sort
      - Quicksort                Algorithms::Sort.quicksort
      - Mergesort                Algorithms::Sort.mergesort
      - Dual-Pivot Quicksort     Algorithms::Sort.dualpivotquicksort

## SYNOPSIS:

    require 'rubygems'
    require 'algorithms'

    max_heap = Containers::MaxHeap.new

    # To not have to type "Containers::" before each class, use:
    include Containers
    max_heap = MaxHeap.new

## REQUIREMENTS:

* Ruby 1.8, Ruby 1.9, JRuby
* C extensions (optional, but very much recommended for vast performance benefits)

## LICENSE:

(The MIT License) WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
