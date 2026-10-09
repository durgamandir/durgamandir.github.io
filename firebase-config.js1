// अपने Firebase प्रोजेक्ट की जानकारी यहाँ भरें (Project settings → Your apps → Web app)
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyCxX5x294mfc639FEK9nN46zqZB3hE-jcM",
  authDomain: "nayagaon-c7794.firebaseapp.com",
  projectId: "nayagaon-c7794",
  storageBucket: "nayagaon-c7794.firebasestorage.app",
  messagingSenderId: "51939588947",
  appId: "1:51939588947:web:398a83b5a13bdc775dbfa6",
  measurementId: "G-0Q3LKYE6BH"
};
firebase.initializeApp(firebaseConfig);
const db = firebase.firestore();
const auth = firebase.auth ? firebase.auth() : null;
const storage = firebase.storage ? firebase.storage() : null;
const $ = id => document.getElementById(id);
const esc = s => String(s ?? '').replace(/[&<>"']/g, c => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
const fmtDate = d => d ? new Date(d + 'T00:00:00').toLocaleDateString('hi-IN', {weekday:'long', day:'numeric', month:'long', year:'numeric'}) : '';
const todayStr = () => { const d = new Date(); return d.getFullYear() + '-' + String(d.getMonth()+1).padStart(2,'0') + '-' + String(d.getDate()).padStart(2,'0'); };
