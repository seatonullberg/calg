sources = files([
    'arraylist.c',
    'avl-tree.c',
    'binary-heap.c',
    'binomial-heap.c',
    'bloom-filter.c',
    'compare-int.c',
    'compare-pointer.c',
    'compare-string.c',
    'hash-int.c',
    'hash-pointer.c',
    'hash-string.c',
    'hash-table.c',
    'list.c',
    'queue.c',
    'rb-tree.c',
    'set.c',
    'slist.c',
    'sortedarray.c',
    'trie.c'
])

calg_lib = library(
    'calg', 
    sources, 
    include_directories: inc,
    install: true,
)

calg_dep = declare_dependency(
    include_directories: inc,
    link_with: calg_lib,
)