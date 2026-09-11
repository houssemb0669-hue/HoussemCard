import { Phone, MessageCircle, Recycle } from "lucide-react";
import "./index.css";

function App() {
  const phone = "0669877641";

  return (
    <main className="page">
      <section className="card">

        <div className="brand-icon">
          <Recycle size={42} strokeWidth={2.2} />
        </div>

        <h1>Houssem</h1>

        <div className="title">
          شراء الحديد والبلاستيك
        </div>

        <p>
          نشتري الحديد والبلاستيك بمختلف أنواعه
        </p>

        <div className="buttons">

          <a
            className="contact-button call"
            href={`tel:${phone}`}
          >
            <span className="button-icon">
              <Phone size={24} />
            </span>

            <span className="button-text">
              <strong>اتصل بي</strong>
              <small>{phone}</small>
            </span>
          </a>

          <a
            className="contact-button whatsapp"
            href="https://wa.me/213669877641"
            target="_blank"
            rel="noopener noreferrer"
          >
            <span className="button-icon">
              <MessageCircle size={25} />
            </span>

            <span className="button-text">
              <strong>واتساب</strong>
              <small>تواصل معي عبر واتساب</small>
            </span>
          </a>

        </div>

        <div className="future">
          <span>روابط التواصل</span>
          <small>سيتم إضافة فيسبوك وتيك توك وغيرها لاحقًا</small>
        </div>

        <div className="footer">
          <span>♻️</span>
          <span>شراء الحديد والبلاستيك</span>
        </div>

      </section>
    </main>
  );
}

export default App;
