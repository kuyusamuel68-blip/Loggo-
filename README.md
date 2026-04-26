DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>NGO Name - Home</title>

    <style>

        body {

            font-family: Arial, sans-serif;

            margin: 0;

            padding: 0;

            background-color: #f4f4f4;

            color: #333;

        }

        header {

            background-color: #00695c;

            color: white;

            padding: 15px 20px;

            text-align: center;

        }

        nav {

            background-color: #004d40;

            display: flex;

            justify-content: center;

        }

        nav a {

            color: white;

            padding: 14px 20px;

            text-decoration: none;

            display: block;

        }

        nav a:hover {

            background-color: #00796b;

        }

        main {

            padding: 20px;

            max-width: 1000px;

            margin: auto;

            background-color: white;

            box-shadow: 0 0 5px rgba(0,0,0,0.1);

        }

        footer {

            background-color: #00695c;

            color: white;

            text-align: center;

            padding: 10px;

            margin-top: 20px;

        }

    </style>

</head>

<body>

 

    <header>

        <h1>NGO Name</h1>

        <p>Working Together for a Better Future</p>

    </header>

 

    <nav>

        <a href="#">Home</a>

        <a href="#">About Us</a>

        <a href="#">Projects</a>

        <a href="#">Get Involved</a>

        <a href="#">Contact</a>

    </nav>

 

    <main>

        <h2>Welcome to Our Organization</h2>

        <p>

            We are committed to making a difference in our community through

            humanitarian aid, education, and sustainable development.

        </p>

 

        <h3>Our Mission</h3>

        <p>

            To bring people together to create lasting solutions to poverty, injustice, and environmental challenges.

        </p>

    </main>

 

    <footer>

        <p>&copy; 2025 NGO Name. All Rights Reserved.</p>

    </footer>

 

</body>

</html>

New Web for unclesam Design

import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { motion } from "framer-motion"; import { Palette, PenTool, Image, Globe } from "lucide-react";

const portfolioItems = [ { title: "Brand Identity Design", category: "Logo & Branding", image: "https://via.placeholder.com/600x400" }, { title: "Business Poster", category: "Print Design", image: "https://via.placeholder.com/600x400" }, { title: "Social Media Flyer", category: "Digital Marketing", image: "https://via.placeholder.com/600x400" }, { title: "Photo Retouching", category: "Image Editing", image: "https://via.placeholder.com/600x400" } ];

export default function UnclesamDesignWebsite() { return ( 

{/* Hero Section */} 

Unclesam Design 

Creative Graphics Design Studio in Kampala, Uganda 

Logos • Branding • Image Manipulation • Web Design • Photography 

Get In Touch 

  {/* About */}  <section className="py-16 px-6 md:px-20 text-center">    <h2 className="text-3xl font-bold mb-4">About Us</h2>    <p className="max-w-3xl mx-auto text-gray-600">      Unclesam Design is a creative graphics design business based in Kampala, Uganda.      We specialize in delivering high-quality visual solutions including corporate branding,      logo creation, digital illustrations, photo editing, and modern web design.      Our mission is to bring ideas to life through creativity and innovation.    </p>  </section>   {/* Services */}  <section className="py-16 bg-gray-100 px-6 md:px-20">    <h2 className="text-3xl font-bold text-center mb-10">Our Services</h2>    <div className="grid md:grid-cols-4 gap-6">      <Card>        <CardContent className="p-6 text-center">          <Palette className="mx-auto mb-2" />          <h3 className="font-semibold">Logo Design</h3>          <p className="text-sm text-gray-500">Unique brand identities</p>        </CardContent>      </Card>       <Card>        <CardContent className="p-6 text-center">          <PenTool className="mx-auto mb-2" />          <h3 className="font-semibold">Graphic Design</h3>          <p className="text-sm text-gray-500">Posters, flyers & branding</p>        </CardContent>      </Card>       <Card>        <CardContent className="p-6 text-center">          <Image className="mx-auto mb-2" />          <h3 className="font-semibold">Image Editing</h3>          <p className="text-sm text-gray-500">Professional retouching</p>        </CardContent>      </Card>       <Card>        <CardContent className="p-6 text-center">          <Globe className="mx-auto mb-2" />          <h3 className="font-semibold">Web Design</h3>          <p className="text-sm text-gray-500">Modern responsive websites</p>        </CardContent>      </Card>    </div>  </section>   {/* Portfolio */}  <section className="py-16 px-6 md:px-20">    <h2 className="text-3xl font-bold text-center mb-10">Our Portfolio</h2>    <div className="grid md:grid-cols-2 lg:grid-cols-4 gap-6">      {portfolioItems.map((item, index) => (        <motion.div          key={index}          whileHover={{ scale: 1.03 }}          className="bg-white rounded-lg shadow-md overflow-hidden"        >          <img            src={item.image}            alt={item.title}            className="w-full h-40 object-cover"          />          <div className="p-4">            <h3 className="font-semibold">{item.title}</h3>            <p className="text-sm text-gray-500">{item.category}</p>          </div>        </motion.div>      ))}    </div>  </section>   {/* Contact */}  <section className="py-16 px-6 md:px-20 text-center">    <h2 className="text-3xl font-bold mb-4">Contact Us</h2>    <p className="text-gray-600">      Kampala, Uganda      <br />      Email: info@unclesamdesign.com (replace if needed)      <br />      WhatsApp: +256 7XX XXX XXX    </p>    <Button className="mt-6">Send Message</Button>  </section>   {/* Footer */}  <footer className="py-6 text-center text-sm text-gray-500 border-t">    © {new Date().getFullYear()} Unclesam Design. All rights reserved.  </footer></div> 

); }

 


