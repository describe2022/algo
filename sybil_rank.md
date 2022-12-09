 Our
algorithm uses the ratio of inter-community degree (number of
edges in a community) and intra-community degree (number
of edges emanating from a community) of each community
in the social graph to differentiate Sybil communities from
honest communities. The intuition is that usually a community
has fewer inter-community connections than intra-community
connections. Also, generally nodes from an honest community
tend to have larger number of inter-community edges with
nodes in other honest communities compared to nodes in
Sybil communities. Again, Sybil nodes may have high intracommunity degree, but they tend to have on an average fewer
connections with honest nodes in other communities. Hence the
ratio of inter-community degree to intra-community degree of
the Sybil nodes in a Sybil community will be smaller than that
of the honest nodes in an honest community. 
