sportSort
=========

A javascript table sorter designed to sort based on sport records (e.g. W-L or W-L-T)

An expansion of the sorttable project that can also sort columns that look like sport records, Win-Loss or Win-Loss-Tie.  

To use download the sportsort.js file, include it with a link in your html file (e.g. <script src="js/sportsort.js"></script>), and give your tables a class of "sortable".  It will pick up most column types (numbers, words, dates) and sort appropriately but does not automatically detect columns that look like sport records and the table columns must be given a class of "sorttable_sport" in order to work.

The original sorttable project and more examples can be found here http://www.kryogenix.org/code/browser/sorttable/  