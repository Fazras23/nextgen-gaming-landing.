import React, { useState } from "react";
import { Card, CardContent } from "./components/ui/card";
import { Button } from "./components/ui/button";
import { Input } from "./components/ui/input";

export default function LandingPage() {
  const [email, setEmail] = useState("");
  const [walletConnected, setWalletConnected] = useState(false);

  const handleSubmit = () => {
    console.log("Email captured:", email);
  };

  const connectWallet = () => {
    if (typeof window.ethereum !== "undefined") {
      window.ethereum.request({ method: "eth_requestAccounts" })
        .then(() => setWalletConnected(true))
        .catch((err) => console.error(err));
    } else {
      alert("MetaMask not detected. Please install it.");
    }
  };

  return (
    <div className="min-h-screen bg-gradient-to-br from-gray-900 to-black text-white p-6 flex flex-col items-center justify-center">
      <h1 className="text-4xl md:text-6xl font-bold text-center mb-4">NextGen Gaming Hub</h1>
      <p className="text-lg md:text-xl text-center max-w-xl mb-6">
        Explore the future of gaming with blockchain access, NFT collectibles, and a simulated stock trading market inside our upcoming app.
      </p>
      <Card className="w-full max-w-md bg-gray-800 rounded-2xl shadow-xl">
        <CardContent className="p-6 space-y-4">
          <Input
            type="email"
            placeholder="Join waitlist with your email"
            className="text-black"
            value={email}
            onChange={(e) => setEmail(e.target.value)}
          />
          <Button onClick={handleSubmit} className="w-full bg-green-500 hover:bg-green-600">
            Join Now
          </Button>
          <Button onClick={connectWallet} className="w-full bg-blue-500 hover:bg-blue-600">
            {walletConnected ? "Wallet Connected" : "Connect Wallet"}
          </Button>
        </CardContent>
      </Card>

      <div className="grid md:grid-cols-3 gap-6 mt-12 max-w-5xl">
        <Feature title="NFT Marketplace" desc="Buy, trade, and show off exclusive in-game NFTs." />
        <Feature title="Stock Simulator" desc="Test your investment skills in a simulated market." />
        <Feature title="Blockchain Access" desc="Connect wallets, join beta, and unlock on-chain rewards." />
      </div>

      <div className="mt-16 w-full max-w-5xl">
        <h2 className="text-2xl font-bold mb-4">Sample NFT Gallery</h2>
        <div className="grid grid-cols-2 md:grid-cols-4 gap-4">
          {[1, 2, 3, 4].map((num) => (
            <div key={num} className="bg-gray-800 rounded-lg overflow-hidden shadow-md">
              <img
                src={`https://placekitten.com/200/20${num}`}
                alt={`NFT ${num}`}
                className="w-full h-40 object-cover"
              />
              <div className="p-2 text-center">NFT #{num}</div>
            </div>
          ))}
        </div>
      </div>

      <div className="mt-16 w-full max-w-5xl">
        <h2 className="text-2xl font-bold mb-4">Mock Stock Portfolio</h2>
        <div className="bg-gray-800 rounded-xl p-4 shadow-md">
          <table className="w-full text-left text-sm">
            <thead>
              <tr>
                <th className="p-2">Company</th>
                <th className="p-2">Shares</th>
                <th className="p-2">Value</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td className="p-2">Gamer Corp</td>
                <td className="p-2">20</td>
                <td className="p-2">$500</td>
              </tr>
              <tr>
                <td className="p-2">ChainPlay Inc</td>
                <td className="p-2">15</td>
                <td className="p-2">$320</td>
              </tr>
              <tr>
                <td className="p-2">VirtualX</td>
                <td className="p-2">10</td>
                <td className="p-2">$290</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  );
}

function Feature({ title, desc }) {
  return (
    <div className="bg-gray-800 p-6 rounded-2xl shadow-md">
      <h3 className="text-xl font-semibold mb-2">{title}</h3>
      <p className="text-sm text-gray-300">{desc}</p>
    </div>
  );
}
