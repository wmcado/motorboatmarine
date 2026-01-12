import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function MotorBoatMarine() {
  return (
    <div className="min-h-screen bg-white text-slate-900">
      {/* Header */}
      <header className="sticky top-0 z-50 bg-navy-900 text-white shadow">
        <div className="max-w-7xl mx-auto flex items-center justify-between p-4">
          <h1 className="text-xl font-bold">MotorBoat Marine</h1>
          <nav className="space-x-4 text-sm">
            <a href="#home">Home</a>
            <a href="#services">Service</a>
            <a href="#sales">Sales</a>
            <a href="#merch">Merchandise</a>
            <a href="#history">History</a>
          </nav>
        </div>
      </header>

      {/* Home */}
      <section id="home" className="bg-slate-100 py-20">
        <div className="max-w-6xl mx-auto px-4 text-center">
          <h2 className="text-4xl font-bold mb-4">Seattle Boat Service, Sales & Gear</h2>
          <p className="text-lg mb-8">
            Full-service marine shop offering professional boat service, boat sales, and MotorBoat Marine merchandise.
          </p>
          <Button className="rounded-2xl">Request Service</Button>
        </div>
      </section>

      {/* Services */}
      <section id="services" className="py-20">
        <div className="max-w-6xl mx-auto px-4">
          <h3 className="text-3xl font-semibold mb-8">Marine Services</h3>
          <div className="grid md:grid-cols-3 gap-6">
            {[
              { title: "Outboard Service", price: "Starting at $250" },
              { title: "Inboard / IO Service", price: "Starting at $350" },
              { title: "Diagnostics & Repair", price: "$150/hr" },
            ].map((s) => (
              <Card key={s.title} className="rounded-2xl shadow">
                <CardContent className="p-6">
                  <h4 className="font-semibold text-lg mb-2">{s.title}</h4>
                  <p className="text-sm">{s.price}</p>
                </CardContent>
              </Card>
            ))}
          </div>
        </div>
      </section>

      {/* Sales */}
      <section id="sales" className="bg-slate-100 py-20">
        <div className="max-w-6xl mx-auto px-4">
          <h3 className="text-3xl font-semibold mb-6">Boat Sales</h3>
          <p className="max-w-2xl">
            We buy, sell, and broker boats of all kinds. From fishing boats to cruisers, we help you find the right fit.
          </p>
        </div>
      </section>

      {/* Merchandise */}
      <section id="merch" className="py-20">
        <div className="max-w-6xl mx-auto px-4">
          <h3 className="text-3xl font-semibold mb-6">Merchandise</h3>
          <p className="mb-4">Apparel, stickers, and gear from MotorBoat Marine.</p>
          <Button variant="outline">Visit Shop</Button>
        </div>
      </section>

      {/* History */}
      <section id="history" className="bg-slate-100 py-20">
        <div className="max-w-6xl mx-auto px-4">
          <h3 className="text-3xl font-semibold mb-6">Our Story</h3>
          <p className="max-w-3xl">
            MotorBoat Marine was founded in Seattle to provide honest service, straightforward sales, and a little banter along the way.
          </p>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-navy-900 text-white py-8">
        <div className="max-w-6xl mx-auto px-4 text-sm flex justify-between">
          <span>© {new Date().getFullYear()} MotorBoat Marine</span>
          <span>motorboatco.com</span>
        </div>
      </footer>
    </div>
  );
}
