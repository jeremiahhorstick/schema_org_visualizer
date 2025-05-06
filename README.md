The Schema.org Visualizer is a web-based tool designed to explore and visualize the Schema.org vocabulary, a structured data markup system used for enhancing web content. This tool provides two interactive views: a Graph View and a Tree View, enabling users to navigate the hierarchical relationships and properties of Schema.org types.

Features:

Graph View: Displays Schema.org types as nodes connected by subclass relationships, using D3.js for force-directed graph rendering. Nodes are color-coded by hierarchy depth, and their size reflects the number of properties. Users can zoom, drag nodes, and click to center on specific types, with a tooltip showing type details.
Tree View: Presents Schema.org types in a collapsible tree structure, starting from the root type "Thing." Users can expand/collapse nodes and click to view detailed information about each type.
Search Functionality: Allows filtering types by name in both views, highlighting matches and centering the view on results in Graph View or scrolling to them in Tree View.
Node Information: A popup displays the type name, description, subclass relationships, and properties when a node is clicked or hovered over (Graph View) or clicked (Tree View).
Responsive Design: Built with a clean, modern UI using system fonts and a blue-themed color scheme, optimized for desktop use with a max-width of 1200px.
Technical Details:

Built with HTML, CSS, and JavaScript, using D3.js (v7.8.5) for graph visualization.
Data is sourced from a comprehensive mock dataset of Schema.org types, including major types like Thing, CreativeWork, Person, Organization, and their subtypes, with properties and hierarchy relationships.
The tool processes data to create a type dictionary and hierarchy structure, supporting dynamic rendering of both views.
Includes zoom and drag interactions in Graph View, with collision detection for node placement.
View switching is seamless, with a loading spinner displayed during initialization.
Usage:

Access the visualizer via a web browser.
Use the search bar to find specific Schema.org types.
Switch between Graph and Tree Views using the control buttons.
Interact with nodes to explore type relationships and details.
Created: May 2025
Data Source: Schema.org
