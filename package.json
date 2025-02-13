import { BrowserRouter as Router, Route, Routes, Link } from "react-router-dom";
import { useState } from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { motion } from "framer-motion";

const Navbar = () => (
  <nav className="p-4 bg-blue-900 text-white flex justify-between items-center">
    <h1 className="text-xl font-bold">Oman Sail</h1>
    <ul className="flex gap-4">
      <li><Link to="/">Home</Link></li>
      <li><Link to="/about">About Us</Link></li>
      <li><Link to="/sailing">Sailing Pathway</Link></li>
      <li><Link to="/events">Events</Link></li>
      <li><Link to="/media">Media Centre</Link></li>
      <li><Link to="/contact">Contact</Link></li>
    </ul>
  </nav>
);

const Home = () => (
  <motion.div className="p-6" initial={{ opacity: 0 }} animate={{ opacity: 1 }}>
    <h2 className="text-2xl font-bold">Welcome to Oman Sail</h2>
    <p className="mt-2">Explore our sailing programs, events, and opportunities.</p>
    <Button className="mt-4">Learn More</Button>
  </motion.div>
);

const About = () => (
  <Card>
    <CardContent className="p-6">
      <h2 className="text-2xl font-bold">About Oman Sail</h2>
      <p className="mt-2">Discover our mission, vision, and the impact we create.</p>
    </CardContent>
  </Card>
);

const SailingPathway = () => (
  <Card>
    <CardContent className="p-6">
      <h2 className="text-2xl font-bold">Sailing Pathway & Programs</h2>
      <p className="mt-2">Learn about our sailing development programs for all ages.</p>
    </CardContent>
  </Card>
);

const Events = () => (
  <Card>
    <CardContent className="p-6">
      <h2 className="text-2xl font-bold">Upcoming Events</h2>
      <p className="mt-2">Check out our upcoming sailing competitions and festivals.</p>
    </CardContent>
  </Card>
);

const MediaCentre = () => (
  <Card>
    <CardContent className="p-6">
      <h2 className="text-2xl font-bold">Media Centre</h2>
      <p className="mt-2">Stay updated with the latest news and media coverage.</p>
    </CardContent>
  </Card>
);

const Contact = () => (
  <Card>
    <CardContent className="p-6">
      <h2 className="text-2xl font-bold">Contact Us</h2>
      <p className="mt-2">Get in touch with us for inquiries and partnerships.</p>
    </CardContent>
  </Card>
);

export default function App() {
  return (
    <Router>
      <Navbar />
      <Routes>
        <Route path="/" element={<Home />} />
        <Route path="/about" element={<About />} />
        <Route path="/sailing" element={<SailingPathway />} />
        <Route path="/events" element={<Events />} />
        <Route path="/media" element={<MediaCentre />} />
        <Route path="/contact" element={<Contact />} />
      </Routes>
    </Router>
  );
}
