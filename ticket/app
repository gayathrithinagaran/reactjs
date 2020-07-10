import React from "react";
import { BrowserRouter, Switch, Route, Link } from "react-router-dom";

import Agent from "./Agent";
import Ticket from "./Ticket";
import Contact from "./Contact"
function App() {
  return (
    <BrowserRouter>
      <div>
        <nav>
          <ul>
            <li>
              <Link to="/agent">Agent</Link>
            </li>
            <li>
              <Link to="/contact">Contact</Link>
            </li>
            <li>
              <Link to="/ticket">Ticket</Link>
            </li>
          </ul>
        </nav>
        <Switch>
          <Route path="/agent" component={Agent} />
          <Route path="/contact" component={Contact} />           
          <Route path="/ticket" component={Ticket} />     
        
        </Switch>
      </div>
    </BrowserRouter>
  );
}

export default App;
