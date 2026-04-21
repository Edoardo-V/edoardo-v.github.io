---
layout: default
title: Publications
permalink: /publications/
order: 3
---

<style>
.publication-section {
  margin-bottom: 3rem;
}

.publication-section h2 {
  border-bottom: 2px solid #e8e8e8;
  padding-bottom: 0.5rem;
  margin-bottom: 1.5rem;
  color: #2c3e50;
}

.publication-item {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 1.5rem;
  padding: 1rem;
  background: #f9f9f9;
  border-left: 3px solid #3498db;
  transition: all 0.3s ease;
}

.publication-item:hover {
  background: #f0f0f0;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.publication-content {
  flex: 1;
  padding-right: 1rem;
}

.publication-item h3 {
  margin-top: 0;
  margin-bottom: 0.5rem;
  font-size: 1.1em;
  color: #2c3e50;
}

.publication-meta {
  font-size: 0.9em;
  color: #666;
  margin-bottom: 0.5rem;
}

.publication-links {
  margin-top: 0;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  gap: 0.5rem;
  min-width: fit-content;
}

.publication-links a {
  margin-right: 1rem;
  color: #3498db;
  text-decoration: none;
}

.publication-links a:hover {
  text-decoration: underline;
}



.award-badge {
  display: inline-block;
  background: #e74c3c;
  color: white;
  padding: 0.2em 0.6em;
  border-radius: 12px;
  font-size: 0.85em;
  font-weight: bold;
  margin-left: 0.5rem;
}

.pub-category-filters {
  display: flex;
  justify-content: center;
  gap: 1rem;
  margin-bottom: 2rem;
  flex-wrap: wrap;
}

.pub-category-filter {
  padding: 0.5rem 1.5rem;
  background: #f5f5f5;
  border: 2px solid #ddd;
  border-radius: 25px;
  cursor: pointer;
  transition: all 0.3s ease;
  font-size: 0.9em;
  text-decoration: none;
  color: #333;
  font-weight: 500;
}

.pub-category-filter:hover,
.pub-category-filter.active {
  background: #3498db;
  color: white;
  border-color: #3498db;
}

.publication-section {
  transition: opacity 0.3s ease;
}

.publication-section.hidden {
  display: none;
}

@media screen and (max-width: 768px) {
  .publication-item {
    padding: 0.75rem;
  }
  
  .publication-item h3 {
    font-size: 1em;
  }
  
  .pub-category-filters {
    gap: 0.5rem;
  }
  
  .pub-category-filter {
    padding: 0.4rem 1rem;
    font-size: 0.85em;
  }
}

@media screen and (max-width: 480px) {
  .publication-item {
    padding: 0.5rem;
  }
  
  .publication-meta {
    font-size: 0.85em;
  }
  
  .citation-count,
  .award-badge {
    display: block;
    margin: 0.5rem 0 0 0;
    width: fit-content;
  }
}
</style>

<div class="pub-category-filters">
  <a href="#" class="pub-category-filter active" data-category="all">All</a>
  <a href="#" class="pub-category-filter" data-category="ai-trading">AI & Trading</a>
  <a href="#" class="pub-category-filter" data-category="space-economy">Space Economy</a>
</div>

<div class="publication-section" id="ai-trading" data-category="ai-trading">
  <h2>AI & Trading</h2>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Time-Inhomogeneous Volatility Aversion for Financial Applications of Reinforcement Learning</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Federico Cacciamani, Roberto Daluiso, Marco Pinciroli, Michele Trapletti, Edoardo Vittori<br>
        <strong>Year:</strong> 2026<br>
        <strong>Venue:</strong> arXiv
      </div>
    </div>
    <div class="publication-links">
      <a href="https://arxiv.org/pdf/2602.12030">PDF</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Reinforcement Learning in Queue-Reactive Models: Application to Optimal Execution</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Tomas Espana, Yadh Hafsi, Fabrizio Lillo, Edoardo Vittori<br>
        <strong>Year:</strong> 2025<br>
        <strong>Venue:</strong> arXiv
      </div>
    </div>
    <div class="publication-links">
      <a href="https://arxiv.org/pdf/2511.15262">PDF</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Leveraging LLMs for Top-Down Sector Allocation in Automated Trading</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Ryan Quek Wei Heng, Edoardo Vittori, Keane Ong, Rui Mao, Erik Cambria, Gianmarco Mengaldo<br>
        <strong>Year:</strong> 2025<br>
        <strong>Venue:</strong> arXiv
      </div>
    </div>
    <div class="publication-links">
      <a href="https://arxiv.org/pdf/2503.09647">PDF</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Optimal Execution with Reinforcement Learning in a Multi-Agent Market Simulator</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Yadh Hafsi, Edoardo Vittori<br>
        <strong>Year:</strong> 2026<br>
        <strong>Venue:</strong> IEEE International Conference on AI for Finance (ICAIF)
      </div>
    </div>
    <div class="publication-links">
      <a href="https://arxiv.org/pdf/2411.06389">PDF</a>
      <a href="https://ieeexplore.ieee.org/abstract/document/11467851">Link</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Exploiting Risk-Aversion and Size-dependent fees in FX Trading with Fitted Natural Actor-Critic</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Vito Alessandro Monaco, Antonio Riva, Luca Sabbioni, Lorenzo Bisi, Edoardo Vittori, Marco Pinciroli, Michele Trapletti, Marcello Restelli<br>
        <strong>Year:</strong> 2024<br>
        <strong>Venue:</strong> arXiv
      </div>
    </div>
    <div class="publication-links">
      <a href="https://arxiv.org/pdf/2410.23294">PDF</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>CVA Hedging with Reinforcement Learning</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Roberto Daluiso, Marco Pinciroli, Michele Trapletti, Edoardo Vittori<br>
        <strong>Year:</strong> 2023<br>
        <strong>Venue:</strong> International Conference on AI for Finance
        <span class="award-badge">Runner-up Best Industrial Paper Award</span>
      </div>
    </div>
    <div class="publication-links">
      <a href="{{ site.url }}/downloads/2023_Daluiso_CVA.pdf">PDF</a>
      <a href="https://dl.acm.org/doi/10.1145/3604237.3626852">Link</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Dealer Markets: a Reinforcement Learning Mean Field Game Approach</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Martino Bernasconi De Luca, Edoardo Vittori, Francesco Trovò, Marcello Restelli<br>
        <strong>Year:</strong> 2023<br>
        <strong>Venue:</strong> The North American Journal of Economics and Finance
      </div>
    </div>
    <div class="publication-links">
      <a href="https://www.sciencedirect.com/science/article/pii/S1062940823000979">Link</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Reinforcement Learning for Credit Index Option Hedging</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Francesco Mandelli, Marco Pinciroli, Michele Trapletti, Edoardo Vittori<br>
        <strong>Year:</strong> 2023<br>
        <strong>Venue:</strong> arXiv
      </div>
    </div>
    <div class="publication-links">
      <a href="https://arxiv.org/pdf/2307.09844.pdf">PDF</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Augmenting Traders with Learning Machines</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Edoardo Vittori<br>
        <strong>Year:</strong> 2022<br>
        <strong>Venue:</strong> PhD dissertation
      </div>
    </div>
    <div class="publication-links">
      <a href="https://www.politesi.polimi.it/bitstream/10589/182998/1/Edoardo_Vittori_PhD_Dissertation.pdf">PDF</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Dark-Pool Smart Order Routing: a Combinatorial Multi-armed Bandit Approach</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Martino Bernasconi De Luca, Stefano Martino, Edoardo Vittori, Francesco Trovò, Marcello Restelli<br>
        <strong>Year:</strong> 2022<br>
        <strong>Venue:</strong> International Conference on AI for Finance
      </div>
    </div>
    <div class="publication-links">
      <a href="{{ site.url }}/downloads/2022_Martino_dark.pdf">PDF</a>
      <a href="https://dl.acm.org/doi/abs/10.1145/3533271.3561728">Link</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Addressing Non-Stationarity in FX Trading with Online Model Selection of Offline RL Experts</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Antonio Riva, Lorenzo Bisi, Pierre Liotet, Luca Sabbioni, Edoardo Vittori, Marco Pinciroli, Michele Trapletti, Marcello Restelli<br>
        <strong>Year:</strong> 2022<br>
        <strong>Venue:</strong> International Conference on AI for Finance
      </div>
    </div>
    <div class="publication-links">
      <a href="{{ site.url }}/downloads/2022_Riva_expertfx.pdf">PDF</a>
      <a href="https://dl.acm.org/doi/abs/10.1145/3533271.3561780">Link</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>MCTS for Trading and Hedging</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Edoardo Vittori, Amarildo Likmeta, Marcello Restelli<br>
        <strong>Year:</strong> 2021<br>
        <strong>Venue:</strong> International Conference on AI for Finance
      </div>
    </div>
    <div class="publication-links">
      <a href="{{ site.url }}/downloads/2021_Vittori_MCTS.pdf">PDF</a>
      <a href="https://dl.acm.org/doi/abs/10.1145/3490354.3494402">Link</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Learning FX Trading Strategies with FQI and Persistent Actions</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Antonio Riva, Lorenzo Bisi, Pierre Liotet, Luca Sabbioni, Edoardo Vittori, Marco Pinciroli, Michele Trapletti, Marcello Restelli<br>
        <strong>Year:</strong> 2021<br>
        <strong>Venue:</strong> International Conference on AI for Finance
      </div>
    </div>
    <div class="publication-links">
      <a href="{{ site.url }}/downloads/2021_Riva_FX.pdf">PDF</a>
      <a href="https://dl.acm.org/doi/abs/10.1145/3490354.3494403">Link</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Conservative Online Convex Optimization</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Martino Bernasconi De Luca, Edoardo Vittori, Francesco Trovò, Marcello Restelli<br>
        <strong>Year:</strong> 2021<br>
        <strong>Venue:</strong> European Conference on Machine Learning
      </div>
    </div>
    <div class="publication-links">
      <a href="https://2021.ecmlpkdd.org/wp-content/uploads/2021/07/sub_271.pdf">PDF</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Dealing with Transaction Costs in Portfolio Optimization: Online Gradient Descent with Momentum</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Edoardo Vittori, Martino Bernasconi De Luca, Francesco Trovò, Marcello Restelli<br>
        <strong>Year:</strong> 2020<br>
        <strong>Venue:</strong> International Conference on AI for Finance
      </div>
    </div>
    <div class="publication-links">
      <a href="{{ site.url }}/downloads/2020_Vittori_OGDM.pdf">PDF</a>
      <a href="https://dl.acm.org/doi/abs/10.1145/3383455.3422531">Link</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Option Hedging with Risk Averse Reinforcement Learning</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Edoardo Vittori, Michele Trapletti, Marcello Restelli<br>
        <strong>Year:</strong> 2020<br>
        <strong>Venue:</strong> International Conference on AI for Finance
      </div>
    </div>
    <div class="publication-links">
      <a href="https://arxiv.org/pdf/2010.12245">PDF</a>
      <a href="https://dl.acm.org/doi/abs/10.1145/3383455.3422532">Link</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Risk-Averse Trust Region Optimization for Reward-Volatility Reduction</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Lorenzo Bisi, Luca Sabbioni, Edoardo Vittori, Matteo Papini, Marcello Restelli<br>
        <strong>Year:</strong> 2020<br>
        <strong>Venue:</strong> International Joint Conference on Artificial Intelligence
      </div>
    </div>
    <div class="publication-links">
      <a href="https://www.ijcai.org/Proceedings/2020/0632.pdf">PDF</a>
    </div>
  </div>

</div>

<div class="publication-section" id="space-economy" data-category="space-economy">
  <h2>Space Economy</h2>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Is the Lunar Economy Solely for the Space Industry? Opportunities for Nonspace Companies in Lunar Infrastructure Leveraging Technological Synergies</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Christophe Bosquillon, Lari Cujko, Gidon Gautel, Derek Webber, Andrea Conconi, Mattia Pianorsi, Simonetta Di Pippo, Edoardo Vittori<br>
        <strong>Year:</strong> 2024<br>
        <strong>Venue:</strong> New Space
      </div>
    </div>
    <div class="publication-links">
      <a href="https://www.liebertpub.com/doi/abs/10.1089/space.2023.0057">Link</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>Preliminary analyses on technical and economic viability of moon-mined propellant for on-orbit refueling</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Andrea Sommariva, Paolo Gaudenzi, Mattia Pianorsi, Michele Pasquali, Edoardo Vittori, Marco Eugeni, Matilde Italiano et al.<br>
        <strong>Year:</strong> 2023<br>
        <strong>Venue:</strong> Acta Astronautica
      </div>
    </div>
    <div class="publication-links">
      <a href="https://www.sciencedirect.com/science/article/pii/S0094576523000061?dgcid=author">Link</a>
    </div>
  </div>

  <div class="publication-item">
    <div class="publication-content">
      <h3>GLINT: Gravitational-wave laser INterferometry triangle</h3>
      <div class="publication-meta">
        <strong>Authors:</strong> Shafa Aria, Rui Azevedo, Rick Burow, Fiachra Cahill, Lada Ducheckova, Alexa Holroyd, Victor Huarcaya, Emilia Jarvel, Martin Koßagk, Chris Moeckel, Ana Rodriguez, Fabien Royer, Richard Sypniewski, Edoardo Vittori, Madeleine Yttergren<br>
        <strong>Year:</strong> 2017<br>
        <strong>Venue:</strong> Experimental Astronomy
      </div>
    </div>
    <div class="publication-links">
      <a href="https://www.researchgate.net/publication/321195945_GLINT_Gravitational-wave_laser_INterferometry_triangle/fulltext/5d6ec8db45851542789f742a/GLINT-Gravitational-wave-laser-INterferometry-triangle.pdf">PDF</a>
    </div>
  </div>

</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const filters = document.querySelectorAll('.pub-category-filter');
  const sections = document.querySelectorAll('.publication-section');

  filters.forEach(filter => {
    filter.addEventListener('click', function(e) {
      e.preventDefault();
      const category = this.getAttribute('data-category');
      
      // Update active state
      filters.forEach(f => f.classList.remove('active'));
      this.classList.add('active');
      
      // Filter sections
      sections.forEach(section => {
        if (category === 'all' || section.getAttribute('data-category') === category) {
          section.classList.remove('hidden');
        } else {
          section.classList.add('hidden');
        }
      });
    });
  });
});
</script>
