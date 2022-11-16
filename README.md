# BÚSQUEDA HEURÍSTICA SIN ADVERSARIOS
#### 1. ¿Qué variable representa la lista ABIERTA?
  La variable 'openSet' de la clase AStar.java (java-algorithms-implementation\src\com\jwetherell\algorithms\graph\AStar.java).

  final List<Graph.Vertex<T>> openSet = new ArrayList<Graph.Vertex<T>>(size);

#### 2. ¿Qué variable representa la función g?
  La función 'g' está representada por la variable 'gScore' de la clase AStar.java.
  
  final Map<Graph.Vertex<T>, Integer> gScore = new HashMap<Graph.Vertex<T>,Integer>();

#### 3. ¿Qué variable representa la función f?
  La función 'f' está representada por la variable 'fScore' de la clase AStar.java.
  
  final Map<Graph.Vertex<T>, Integer> fScore = new HashMap<Graph.Vertex<T>,Integer>();

#### 4. ¿Qué método habría que modificar para que la heurística representara la distancia aérea entre vértices?
  Tendríamos que modificar el método 'aStar' de la clase AStar.java.
  
  public List<Graph.Edge<T>> aStar(Graph<T> graph, Graph.Vertex<T> start, Graph.Vertex<T> goal) {...}

#### 5. ¿Realiza este método reevaluación de nudos cuando se encuentra una nueva ruta a un determinado vértice? Justifique la respuesta.
