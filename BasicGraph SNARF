/*
 * Assignment: BasicGraph
 * Name: TODO
 * Date: TODO
 *
 * IMPORTANT: READ ALL INSTRUCTIONS BEFORE BEGINNING THIS ASSIGNMENT
 *
 * Complete your implementation of the BasicGraph class, which represents a set of Vertexes
 * along with the Edges connecting them (this will require implementing Vertex and Edge classes
 * as well). To aid with your implementation, we have included the prototypes of all the functions
 * you need to define in order to properly create and use a BasicGraph. Feel free to define any
 * other helper functions that will make your life easier :)
 *
 */


/*
 * Constructor for a Vertex object. Properties of a Vertex include:
 *
 * double cost			The cost to reach this vertex; initially 0.
 * Array<Edge> edges	A set of pointers to all outbound edges from this vertex.
 * string name			The name of this vertex in the graph.
 * Vertex previous		A pointer to a previous vertex; initially NULL.
 * bool visited			Whether or not this vertex has currently been visited; initially false.
 *
 *
 * You should also include resetData() and toString() functions. See this link for their
 * documentation: http://stanford.edu/~stepp/cppdoc/Vertex-class.html
 */
function Vertex(name) {
	// TODO: Implement the properties and functions described above.

}


/*
 * Constructor for an Edge object. Properties of an Edge include:
 *
 * double cost		The cost or weight of this edge.
 * Vertex end		A pointer to the finishing vertex touching this edge.
 * Vertex finish	A pointer to the finishing vertex touching this edge.
 * Vertex start		A pointer to the starting vertex touching this edge.
 * bool visited		Whether or not this edge has currently been visited; initially false.
 *
 *
 * You should also include resetData() and toString() functions. See this link for their
 * documentation: http://stanford.edu/~stepp/cppdoc/Edge-class.html
 */
function Edge(start, end, cost) {
	// TODO: Implement the properties and functions described above.
	
}

/*
 * Constructor for a BasicGraph object. Functions needed for a BasicGraph include:
 *
 * addEdge(v1, v2) 		Adds an edge to the graph.
 * addVertex(v) 		Adds a vertex to the graph.
 * clear() 				Removes all vertexes and edges from the graph.
 * clearEdges()			Removes all edges from the graph.
 * containsEdge(v1, v2) Returns whether the graph has an edge between the given two vertexes.
 * containsVertex(v)	Returns whether the graph has an edge between the given two vertexes.
 * getEdge(v1, v2)		Returns the edge between the given two vertexes.
 * getEdgeSet()			Returns the set of all edges in the graph.
 * getEdgeSet(v)		Returns the set of all edges that start at the specified vertex.
 * getNeighbors(v)		Returns the set of vertexes that are neighbors of the specified vertex, which can be indicated either as a pointer or by name.
 * getVertex(name) 		Looks up a vertex in the name table attached to the graph and returns that vertex.
 * getVertexSet() 		Returns the set of all vertexes in the graph.
 * isEmpty()			Returns true if the graph contains no vertexes or edges.
 * isNeighbor(v1, v2)	Returns true if the graph contains an edge from v1 to v2.
 * removeEdge(v1, v2)	Removes an edge from the graph, specified by the vertexes at its endpoints
 * removeVertex(name)	Removes a vertex from the graph, specified by its name
 * resetData() 			Clears any temporary internal data stored at each vertex and edge.
 * size()				Returns the number of vertexes in the graph.
 * toString() 			Converts the graph to a printable string representation.
 *
 *
 * IMPORTANT: See this link for their documentation --> http://stanford.edu/~stepp/cppdoc/BasicGraph-class.html
 */
function BasicGraph() {
	// TODO: Implement the properties and functions described above.
	
}




// TEST CODE: Do not modify this code. Use it to ensure that your implementations of the
// above 3 classes are correct!

var graph = new BasicGraph();

var v1 = new Vertex("Penguin Paradise");
var v2 = new Vertex("Toucan Tundra");
var v3 = new Vertex("Flamingo Forest");
var v4 = new Vertex("Hummingbird Hotsprings");
var v5 = new Vertex("Uncle Rico");
var v6 = new Vertex("Chris Fleming");

var e1 = new Edge(v1, v3, 20);
var e2 = new Edge(v1, v6, 420);
var e3 = new Edge(v3, v5, 15);
var e4 = new Edge(v3, v2, -4);
var e5 = new Edge(v2, v4, 5);
var e6 = new Edge(v5, v4, 4);

var vertArr = [v1, v2, v3, v4, v5, v6];
var edgeArr = [e1, e2, e3, e4, e5, e6];

vertArr.forEach( function(v) { graph.addVertex(v); });
edgeArr.forEach( function(e) { graph.addEdge(e); });

console.log(graph.toString());


